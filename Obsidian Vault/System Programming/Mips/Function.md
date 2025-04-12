### Idea
![[mips_functions.pdf#page=7]]
#### Jal and Jr
jal also increments $ra by 4 bytes to skip to the next instruction.
![[mips_functions.pdf#page=8]]
#### Return value and parameters
![[mips_functions.pdf#page=10]]
#### Function calling another function
function that doesn't call other function are leaf function and does not require begin, end, push and pop
![[mips_functions.pdf#page=19]]

### Example
```c
#include <stdio.h>

void two(int i);

int main(void) {
    two(1);
}

void two(int i) {
    if (i < 1000000) {
        two(2 * i);
    }
    printf("%d\n", i);
}
```

```asm
main:
    begin               # move frame pointer
    push  $ra           # save $ra onto stack

    li    $a0, 1
    jal   two           # two(1);

    pop   $ra           # recover $ra from stack
    end                 # move frame pointer back

    li    $v0, 0        # return 0
    jr    $ra           #


two:
    begin               # move frame pointer
    push  $ra           # save $ra onto stack
    push  $s0           # save $s0 onto stack

    move  $s0, $a0

    bge   $a0, 1000000, two_end_if
    mul   $a0, $a0, 2
    jal   two
two_end_if:

    move  $a0, $s0
    li    $v0, 1        # printf("%d");
    syscall

    li    $a0, '\n'     # printf("%c", '\n');
    li    $v0, 11
    syscall

    pop   $s0           # recover $s0 from stack
    pop   $ra           # recover $ra from stack
    end                 # move frame pointer back

    jr    $ra           # return from two
```
All of the $s0 and $ra has been stored onto the stack so, the function can go back to them 
and access them.

#coding #MIPS



