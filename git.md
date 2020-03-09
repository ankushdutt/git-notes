# Git
### What?
- A version control system for tracking changes in source code.

### Why?
- Fast and efficient as it **stores the change in source code** (in .git file) rather than creating a copy of file with different versions.
- Makes collaboration easier, allowing changes by multiple people to all be merged into one source.

### What is Github?
    An online platform which work through Git. Other alternatives are "Gitlab", "Bitbucket".

### Steps to Create (local) Git respository:
1. `git init`
2. `git add .` To push in *Staging Area*.
3. `git commit -m "Your message here, preferred in Simple Present Tense"` To push in *Commit Area*.

### Steps to add (local) Git respository to Github:
1. Create a new respository on *Github*.
2. `git remote add origin (your branch)`
3. `git push origin master`

### Important points:
- Use `git status` to show changes in files/codes.
- **(your branch)** is provided by *Github* after you create a respository.
- **origin** is preferred name to refer to *Github*. Any other name can also be used. This is also correct: `git remote add notorigin (your branch)` followed by `git remote push notorigin master`