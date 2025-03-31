# Guide to Using Git with GitHub

## 1. Clone a Repository
To copy a repository from GitHub to your computer, use the following command:
```sh
git clone <repo-URL>
```
Example:
```sh
git clone https://github.com/user/repository.git
```

## 2. Add Files to Git and Commit
After making changes or adding new files, add them to Git:
```sh
git add .
```
Commit the changes:
```sh
git commit -m "Description of changes"
```

## 3. Push Code to GitHub
After committing, push the code to GitHub:
```sh
git push origin <branch-name>
```
Example:
```sh
git push origin master
```
If an error occurs due to the remote branch being ahead, pull the changes first:
```sh
git pull --rebase origin master
```
Then push again:
```sh
git push origin master
```

## 4. Pull the Latest Code from GitHub
To get the latest code from a GitHub repository:
```sh
git pull origin <branch-name>
```
Example:
```sh
git pull origin master
```

## 5. Check Repository Status
To see uncommitted changes:
```sh
git status
```

## 6. View Commit History
To check the list of recent commits:
```sh
git log --oneline
```

## 7. Configure Git for the First Time
Before working with Git, set up your personal information:
```sh
git config --global user.name "Your Name"
git config --global user.email "email@example.com"
```

