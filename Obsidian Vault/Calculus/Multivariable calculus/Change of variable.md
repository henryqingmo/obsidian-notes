### Idea
![[12. Change of Variable - Annotated.pdf#page=2]]
We can think of the mapping as changing the coordinate systems
![[12. Change of Variable - Annotated.pdf#page=3]]
Here each grid in the $(r,\theta)$ plane is scaled by a factor determined by the determinant of [[Jacobian matrix]]
![[Dr. Trefor Bazett - Change of Variables & The Jacobian Multi-variable Integration [wUF-lyyWpUc - 1047x589 - 4m51s].png]]
This is similar to the idea of [[Chain rules]] in 1D calculus
![[IMG_0416 1.jpeg]]
Here we expressed $dx$ and $dy$ in terms of their [[Differentials and best affine approximation]]. 

### Formally
The order of integration does matter and might change after a change of variable, which can be determined by their dependency.
![[Pasted image 20250405235702.png]]
### Example
![[12. Change of Variable - Annotated.pdf#page=23]]
![[Pasted image 20250405235851.png]]
```python
for θ in [0, 2π]:         // outer
    for r in [0, √a]:     // middle
        for z in [0, e^{-r²}]:  // inner (depends on r)
            volume += r * 1
```

#math #calculus 



