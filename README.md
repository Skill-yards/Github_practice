# Git Practice for Students

Welcome to the Git practice exercise! In this exercise, you will practice the basics of Git and GitHub by working through a series of tasks that cover:

- Cloning a repository
- Branching and merging
- Staging and committing changes
- Pushing changes to a remote repository
- Creating pull requests

Follow the steps below to complete the exercise.

---

## Getting Started

### 1. Clone the Repository
First, clone this repository to your local machine using the command:
```bash
https://github.com/amitvsk/Html_practice.git
```

### 2. Create a New Branch
Create a new branch for your work:
```bash
git checkout -b feature-branch
```

### 3. Make Changes
In this step, you will create a new file or edit an existing one.

- Create a new file named `myfile.txt` in the root of the project.
- Add some content to the file, like:
  ```text
  This is my first Git practice!
  ```

### 4. Stage Your Changes
After making your changes, stage the new file:
```bash
git add myfile.txt
```

### 5. Commit Your Changes
Now, commit your changes with a meaningful message:
```bash
git commit -m "Added myfile.txt with practice content"
```

### 6. Push the Changes to GitHub
Push your new branch to GitHub:
```bash
git push origin feature-branch
```

### 7. Open a Pull Request
Go to your GitHub repository and open a pull request from `feature-branch` to the `main` branch.

---

## Additional Practice Tasks

1. **Modifying an Existing File**: Edit the `README.md` file and add your name to the contributors list.
   
2. **Branching Practice**: Create another branch, make some changes (e.g., add a new section to `README.md`), and push those changes to a new branch.

3. **Merge Conflicts**: Simulate a merge conflict by editing the same line in `README.md` in two different branches. Resolve the conflict when merging.

4. **Reverting Commits**: After pushing a change, learn how to use `git revert` to undo it.



### Practice Task Summary:

1. **Clone the repository**: `git clone <repo-url>`
2. **Create a new branch**: `git checkout -b feature-branch`
3. **Make changes**: Create or modify a file, like `myfile.txt`
4. **Stage the changes**: `git add myfile.txt`
5. **Commit the changes**: `git commit -m "Added a new file"`
6. **Push the changes**: `git push origin feature-branch`
7. **Open a pull request** on GitHub
8. **Extra tasks**:
   - Add your name to `README.md`
   - Create a branch, make changes, and resolve a merge conflict
