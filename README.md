## Repo Github Tutorial

### Clone
Save a repository locally

```git
git clone <repo_id>
```

### Pull
Pull changes made into the repository after cloning.

```git
# Open an existing repository / repository you are working on and enter
git pull
```

### Branch
See all branches
```git
# Add -a flag at the end to see all branches from Local and the remote repo
git branch --list
```

Open a new branch

```git
git branch <Branch_Name>
```

Change to new branch

```git
git checkout <Branch_Name>
```


### Incase of Conflicts
### Rebase 
**Rebase = True** will change the repo head to the ***Changes that you have made in your local repo***
```git
git pull --rebase=False
```
**Rebase = False** will change the repo head to the ***Changes that you have made in your local repo***
```git
git pull --rebase=False
```

```git
git pull --rebase=interactive
```
