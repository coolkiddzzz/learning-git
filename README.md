# Learning Git
This is my repo for learning git. 

## Github Authentication
What is GitHub Authentication and how what methods available to be implemented?
- It keeps your account and data secure with features like two-factor authentication, SSH, and commit signature verification.
- Methods available: 
  - Username & Password
  - Two-factor authentication (2FA) (time-based one time password )
  - SAML single sign-on

Reference: [Documentation](https://docs.github.com/en/authentication)

# Git Commands
| Command | Usage | 
| ------ | ------ |
| git init                          | initialize an existing directory as a Git repository                     |
| git clone [url]                   | Retrieve an entire repository from a hosted location via URL             |
| git pull                          | fetch and merge any commits from the tracking remote branch              |
| git add .                         | add a file as it looks now to your next commit (stage)                   | 
| git commit -m "message"           | commit your staged content as a new commit snapshot                      | 
| git push -u origin [branch-name]  | Transmit local branch commits to the remote repository branch            | 
| git merge [branch]                | merge the specified branch’s history into the current one                |
| git branch                        | list your branches. a * will appear next to the currently active branch  | 
| git branch [branch-name]          | create a new branch at the current commit                                |
| git checkout [branch-name]        | switch to another branch and check it out into your working directory    | 
| git branch -d [branch-name]       | deleting branch                                                          | 
| git log                           | show all commits in the current branch’s history                         |

## Most Commonly Used Commands 
These commands are used for creating a branch and merge with the main branch. These are commonly used for collaboration among team members when working on the code. 
- Git add, Git commit, Git push, Git merge

Detailed steps for git branch merging are as per follows:
- git init 
- git pull
- git branch [branch-name]
- git checkout [branch-name]
- git add .
- git commit -m 'message'
- git push -u origin [branch-name]
- git checkout master 
- git merge [branch-name]




