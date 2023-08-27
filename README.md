# Git-Commands-To-Add-Project-In-Existing-Repo


# Example Website Repository

This repository contains the files for the Example Website project. Here's how you can set up the repository and push your files to GitHub using Git commands. :octocat:

## Getting Started

Follow these steps to initialize the repository, add your project files, and push them to GitHub.

### Prerequisites

- Git installed on your local machine
- GitHub account

### Initialization

1. **Open your terminal.**
2. **Navigate to the directory where your project files are located using the `cd` command.**
3. **Initialize a new Git repository using the command:**

   ```shell
   git init
   ```

### Adding Files

1. **Add all the project files to the staging area using the command:**

   ```shell
   git add .
   ```

   The `.` symbol means that all files in the current directory will be added. You can also specify individual files if needed.

### Committing Changes

1. **Commit the staged files with a descriptive message using the command:**

   ```shell
   git commit -m "Add existing project files to Git"
   ```

   Replace `"Add existing project files to Git"` with a concise and meaningful commit message that explains what you've done.

### Linking to Remote Repository

1. **Create a new repository on GitHub. Let's assume the repository URL is `https://github.com/cameronmcnz/example-website.git`.**

2. **Link your local repository to the remote GitHub repository using the command:**

   ```shell
   git remote add origin https://github.com/cameronmcnz/example-website.git
   ```

   Replace the URL with your repository's URL.

### Pushing to GitHub

1. **Push your committed changes to the remote repository's `master` branch using the command:**

   ```shell
   git push -u -f origin master
   ```

   The `-u` flag sets up the tracking relationship for the branch, and the `-f` flag forces the push even if there are upstream changes. Be cautious when using the force push option.

## 🚀 Voila!

Your project files are now uploaded to GitHub! You can view them in your GitHub repository. Remember to continue using Git commands to manage and update your repository as needed. Happy coding! :rocket:
```

