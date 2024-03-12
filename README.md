# Git Branching and Collaboration README

This README provides an overview of Git branching and collaboration using a real-world example. The following steps demonstrate the creation of a new branch named 'ernest,' making changes, committing them, and pushing the changes to a remote repository. Additionally, it shows how to create a pull request and merge changes back into the main branch.

## Git Branching

### Create a New Branch
To create a new branch named 'ernest,' use the following commands:
```bash
git branch ernest
```

### View Branches
To view the available branches and the current branch (marked with '*'), use:
```bash
git branch
```
In the example, the branches are 'ernest' and 'main.'

### Switch to a Branch
To switch to the 'ernest' branch, use:
```bash
git checkout ernest
```

### Commit Changes on the Branch
After making changes to the project files, add and commit them using:
```bash
git add .
git commit -m "projects file commit"
```

### Push Changes to Remote Repository
To push the changes to the 'ernest' branch on the remote repository, use:
```bash
git push origin ernest
```
This command creates a pull request on GitHub.

## Collaboration

### Switch Back to Main Branch
To switch back to the 'main' branch, use:
```bash
git checkout main
```

### Pull Changes from Remote Main Branch
To ensure the local 'main' branch is up to date, pull changes from the remote repository:
```bash
git pull origin main
```

This README provides a basic overview of Git branching and collaboration. Users can adapt these steps to their projects, ensuring a systematic and collaborative development process. For more advanced collaboration, consider additional Git features such as merging, rebasing, and resolving conflicts.
