# Version-Control-and-Git-Task-2 


## 1. Explain Version Control

Version control is a system that helps developers track changes made to files over time. It allows you to:
- Keep a history of changes
- Revert to previous versions if needed
- Collaborate with others without overwriting work

Popular version control systems include Git.

---

## 2. Explain the difference between Git and GitHub

| Git | GitHub |
|-----|--------|
| Git is a version control system | GitHub is a cloud-based hosting platform |
| Works locally on your computer | Works online |
| Tracks changes in code | Stores and manages Git repositories |
| Does not require internet | Requires internet |

---

## 3. LIst 3 other GitHub Alternatives

1. GitLab  
2. Bitbucket  
3. SourceForge  

---

## 4. Explain the difference between `git fetch` and `git pull`

| git fetch | git pull |
|-----------|----------|
| Downloads changes from remote repository | Downloads and merges changes |
| Does not change your working files | Updates your working directory |
| Safer for checking updates first | Directly updates your project |

---

## 5. Explain in simple terms Git Rebase and the command for it 

Git rebase is used to move or combine a sequence of commits to a new base commit. It helps maintain a clean project history.

### Command:

git rebase main 

----

## 6. Explain in simple terms Git Cherry-Pick and the command for it 

Git cherry-pick is used to apply a specific commit from one branch to another.

### Command:

git cherry-pick <commit-hash>

---