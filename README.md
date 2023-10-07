# Into to git and GitHub

This README file walks you through

- Creating a GitHub repository from scratch
- Use git Version Control System (VCS) to interactg with GitHub remote repository

## **Log in to your GitHub account**

1. [GitHub Login](https://github.com/login)

2. Click on [New](https://github.com/new) to create a new repository

- You can also navigate to "Your repositories" under your avatar icon (top right) to create a new repo

1. 2a. Choose a Repository name: Test01
2. 2b. Make your repo private or public
3. 2c. Add a README file
4. 2d. Create repository <br>

## **Clone remote repo to local working directory**

1. Open command prompt on Windows

2. Create a new directory called **repo-test**

   ```
   mkdir repo-test
   ```

3. Change directory to repo-test

   ```
   cd repo-test
   ```

4. Check if you have git with your command prompt:

   ```
   git --version
   ```

- If not, then [Download](https://git-scm.com/downloads) git VCS if you don't have git in your system

5. Clone the **tes01** repo we created at the beginning

   ```
   git clone https://github.com/<GitHubUserName>/Test01.git
   ```

6. Navigate to Test01 repo

   ```
   cd Test01
   ```

**This is your Test01 repository with a README file** <br>

## **Update README file & update Remote GitHub repository**

1. Open README file and update the content of the README.md file and save the file

   ```
   README.md
   ```

2. From Workspace (working directory) **add** your work to the **Stagin Area**
<pre>
git add .                           // add . to stage all changes
</pre>

3. **Commit** your work with a message to the **Local Repository**
<pre>
git commit -m "README file updated" // -m for the commit message
</pre>

4. Finaly **push** your work to the **Remote Repository**
<pre>
git push
</pre>

:smile: :+1:
