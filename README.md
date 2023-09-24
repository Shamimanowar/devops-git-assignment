# Git Assignment

This repository contains the files and instructions for the Git assignment. The purpose of this assignment is to help you practice using Git for version control, collaboration, and code management.

## Assignment Instructions

Follow these steps to complete the assignment:

1. **Fork this repository:** Click the "Fork" button in the upper right-hand corner of the repository's page on GitHub. This will create a copy of the repository in your GitHub account.

2. **Clone your fork:** Use the `git clone` command to clone your forked repository to your local machine.

    ```bash
    git clone git@github.com:Shamimanowar/devops-git-assignment.git
    ```

3. **Create a branch:** Create a new branch to work on your changes. Give your branch a descriptive name that reflects the task you are working on.

    ```bash
    git checkout -b feature/add-new-feature
    ```

4. **Make changes:** Edit, add, or delete files as necessary to complete the assigned task.

5. **Commit your changes:** Use `git commit` to commit your changes with a meaningful commit message.

    ```bash
    git add .
    git commit -m "Add a new feature: Description of the feature"
    ```

6. **Push your changes:** Push your branch to your GitHub repository.

    ```bash
    git push origin feature/add-new-feature
    ```

7. **Create a Pull Request (PR):** Go to your GitHub repository and click on the "New Pull Request" button. Make sure to compare your branch with the original repository's `main` branch. Write a clear description of your changes in the PR.

8. **Review and Merge:** After creating the PR, your instructor or a designated reviewer will review your code. They may provide feedback or request changes. Once the changes are approved, the PR will be merged into the main repository.

9. **Update your fork:** Periodically, you should update your fork with changes from the original repository by syncing your fork.

    ```bash
    git fetch upstream
    git checkout main
    git merge upstream/main
    git push origin main
    ```

## Submission

Submit your assignment by creating a Pull Request (PR) in the original repository. Make sure to follow the assignment instructions and include a clear description of your changes in the PR.

## Resources

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)

Happy coding!
