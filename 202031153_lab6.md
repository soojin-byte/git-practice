# Git-1



### Version Control system for software development
> when you save your project, named 프로젝트_최종, 프로젝트_최종_수정1


### Three Staes in Git
- (Comitted)git directory -> checkout the project -> (Modified)working directory
- (Modified)working directory -> stage fixes -> (Staged)staging area
- (Staged)staging area -> commit ->(Comitted)git directory

---

### Git config: First-time setup
>There are 3 levels                        
             
(1) System level: --system option. Affects all uses and repositories on the system (administrative)               
(2) Global (user) level: --global option. Affects all repositories of a current user            
(3) Local level: --local option. Specific to the current repository                

---

### Initializing a Repository in an Existing Directory
``` sh
$ git init
```

### Checking Repository Status
``` sh
$ git status
```

### Adding a new file to be staged (tracked)
``` sh
$ git add[file_name]
```

### Adding all files to be staged (tracked)
``` sh
$ git add.
```

### Unstaging a file
``` sh
$ git rm --cached[file_name]
```

### Commit
``` sh
$ git commit -m “commit message”
```
