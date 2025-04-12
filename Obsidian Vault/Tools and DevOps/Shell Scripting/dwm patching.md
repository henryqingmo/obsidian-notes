

Find patches from https://dwm.suckless.org/patches/
Save the diff file to Suckless/dwm/patches
First check if latest changes were commited
```
git status
```
Create a new git branch using ```
```
git branch branchname
```
Switch to that branch
```
git checkout branchname
```
patching  
```
patch -p1 < patches/patchname.diff
```
If patched to config.def.h
```
sudo cp config.def.h config.h
```
compile the code
```
sudo make clean
```
fix any conflicts and install the compiled binary
```
sudo make clean install
```
save and commit all changes by
```
git add.
git commit -m "added patch"
```
switch to master branch and merge
```
git checkout master
git merge -m branchname "patched branchname"
```
Push to github
```
git push -u origin master
```
