# Into to git and GitHub

This README file walks you through creating a GitHub repository from scratch with git Version Control System (VCS).

## Create a new Repository

1. ### **Log in to your GitHub account**


- [GitHub Login](https://github.com/login)

- Click on [New](https://github.com/new) to create a new repository

  - You can also navigate to "Your repositories" under your avatar icon (top right) to create a new repo

- Choose a Repository name Test01
- private or public
- Add a README file
- Create repository


### 2. **Clone remote repo to local working directory**


- Open command prompt on Windows

- Create a new directory called **repo-test**
  ```
  mkdir repo-test
  ```
- Change directory to repo-test
  ```
  cd repo-test
  ```
- Clone the **tes01** repo we created at the beginning
  ```
  git clone https://github.com/<GitHubUserName>/Test01.git
  ```
- Navigate to Test01 repo

  ```
  cd Test01
  ```

- This is your Test01 repository with a README file


3. ### **Update README file & update Remote GitHub repository**


- Open README file and update the content of the README.md file and save the file
  ```
  README.md
  ```
- From Workspace (working directory) **add** your work to the **Stagin Area**
  ```
  git add . // add . to stage all changes
  ```
- **Commit** your work with a message to the **Local Repository**
  ```
  git commit -m "README file updated" // -m for the commit message
  ```
- Finaly **push** your work to the **Remote Repository**
  ```
  git push
  ```

:smile: :+1:
