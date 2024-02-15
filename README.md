# demo-repo
Repo for demoing branching


## 1 - Setup on remote GiHub




## 2 - Clone (HTTPS)

### Clone

https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository

```shell
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

```shell
git clone https://github.com/rileyalbiston/demo-repo.git
```

Or just a specific brach

```shell
git clone -b <branchname> <remote-repo-url>
```

```shell
git clone -b branch-1 https://github.com/rileyalbiston/demo-repo.git
```


--------------- OR ----------------------------

https://www.freecodecamp.org/news/git-clone-branch-how-to-clone-a-specific-branch/

```shell
git clone -b <branchname> --single-branch <remote-repo-url>
```
## Lists all the branches from the local repository

```shell
git branch -a
```

## Just Just the current branch

```shell
git branch --show-current
```


## Change branch

https://git-scm.com/docs/git-switch

```shell
git switch branch-1
```

## 3 - Make change is branch-1

Do stuff

git status

git add file-2-in-branch-1.txt

git commit -m "Added file 2"

## 4 - Push to remote

https://docs.github.com/en/get-started/using-git/pushing-commits-to-a-remote-repository

```shell
git push origin localBranchName:remoteBranchName
```


```shell
git push origin branch-1:branch-1
```

## 5 - Pull from just branch-2

```shell
git clone -b branch-2 --single-branch https://github.com/rileyalbiston/demo-repo.git
```
 
