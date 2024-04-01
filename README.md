# git--basics updated 
```bash
apt git install
yum git install
```
 to install git 
```bash
git init
````
 to initialize and create repo 

```bash
git status
```

it will show the status
```bash
git add
````
to track the files 
```bash
git commit -m <uploadins content with version > 
 ```
commit the changes to local repo and here commits will act as kind of snapshots. when we use commit it create new commit id  everytime. when we want to revert back changes we can use this commit ids . u can fins this commit ids by giving git log.

```bash
git log
````  
it will show the previous commit history with commit ids.
```bash
git diff
```

- to check diffrenece b/w the files before edit and after edit
```bash
git reset --hard 339ae0a626cda8d12437d0e6fb4ad267c587ba5f 
````
 -git reset --hard < commit id >  it will revert back the commits with commit id
