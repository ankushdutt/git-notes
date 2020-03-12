# Git
### What?
- A version control system for tracking changes in source code.

### Why?
- Fast and efficient as it **stores the change in source code** (in .git file) rather than creating a copy of file with different versions.
- Makes collaboration easier, allowing changes by multiple people to all be merged into one source.

### What is Github?
An online platform which work through Git. Other alternatives are [Gitlab](https://about.gitlab.com), [Bitbucket](https://bitbucket.org/product).

### Steps to Create (local) Git repository:
1. `git init`
2. `git add .` To push in **Staging Area**.
3. `git commit -m "Your message here, preferred in Simple Present Tense"` To **Commit**.

### Steps to Add (local) Git repository to Github:
1. Create a new repository on *Github*.
2. `git remote add origin <url>` Required **only once** for a particular repository unless `git remote rm origin` is used. <**url**> is provided by *Github* after you create a repository.
3. `git push origin master`

### Important points:
- Store file/folder names in `.gitignore` file (for a particular repository) to ignore git commands on them.
- Use `git status` to show changes in files/codes. 
- **origin** is preferred name to refer to *Github*. Any other name can also be used. This is also correct: `git remote add notorigin <url>` followed by `git remote push notorigin master`.
- Use `git log --all` to show all the commits with id.
- Use `git checkout <id>` to currently use that commit.

### Steps to Contribute to Open Sources on Github:
1. Fork the **upstream**.
2. Clone the **origin master** on your PC (local) using `git clone <url>`.
3. `git checkout -b <new-branch>` to create and switch to a new branch.
4. Do neccessary changes to contribute and **Commit**.
5. Use `git push origin <new-branch>` from the <**new-branch**>.
6. Make a pull request to merge **origin** <**new-branch**> with **upstream master** from Github.
