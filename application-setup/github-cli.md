# GitHub CLI

## Installation

Open Terminal, and run the following command to install GitHub CLI:

```
sudo dnf install gh
```

## Login

Run `gh auth login`, and answer each prompt like below:

```
What account do you want to log into: GitHub.com
What is your preferred protocol for Git operations: SSH
Generate a new SSH key to add to your GitHub account: Yes
Enter a passphrase for your new SSH key: Enter any password
Title for your SSH key: Enter any title
How would you like to authenticate GitHub CLI: Login with a web browser
```

## Settings

Run the following to set user information:

```
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```
