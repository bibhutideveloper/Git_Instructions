The process of creating a new repository on GitHub using the command line. Before you start, make sure you have Git installed on your machine and that you have a GitHub account.

Here are the steps:

1. **Create a New Repository on GitHub:**
   - Go to [GitHub](https://github.com/) and log in to your account.
   - Click on the "+" icon in the top right corner and select "New repository".

2. **Fill in Repository Information:**
   - Give your repository a name.
   - Optionally, add a description.
   - Choose between public and private (if you have a paid GitHub account).
   - Initialize this repository with a README if you want to start with a README file.

3. **Create the Repository:**
   - Click the "Create repository" button.

Now, let's move to the command line:

4. **Open your terminal or command prompt:**
   - Navigate to the directory where you want to create your new project.

5. **Initialize a Git repository:**
   - If your project already has code, navigate to the project's root directory using the `cd` command.
   - Run the following commands to initialize a Git repository:

     ```bash
     git init
     ```

6. **Add a remote repository:**
   - Copy the URL of the repository you created on GitHub.
   - Run the following command, replacing `<repository_url>` with the URL you copied:

     ```bash
     git remote add origin <repository_url>
     ```

7. **Add your files:**
   - If you have existing files in your project, add them to the staging area:

     ```bash
     git add .
     ```

   - If you don't have any files yet, create at least one file and add it:

     ```bash
     echo "# My Project" > README.md
     git add README.md
     ```

8. **Commit your changes:**
   - Commit the changes to the local repository:

     ```bash
     git commit -m "Initial commit"
     ```

9. **Push to GitHub:**
   - Push the changes to the remote repository on GitHub:

     ```bash
     git push -u origin master
     ```

   - This command sets the upstream branch and pushes your changes.

Now, your local repository is connected to the GitHub repository, and your code is uploaded. Refresh your GitHub repository page, and you should see your files.
