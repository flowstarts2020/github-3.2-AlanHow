# github-3.2-AlanHow
assignment 3.2

What is GitHub Authentication and how what methods available to be implemented?

GitHub authentication is the process of verifying the identity of a user or application that wants to interact with GitHub's services. Authentication is required to perform any action on GitHub, such as pushing code changes, opening or commenting on issues, or accessing user data. GitHub offers several authentication methods that can be implemented to verify user or application identity:

Username and password: This is the most common authentication method. Users enter their GitHub username and password to authenticate with the service. This method is not recommended for applications, as it requires the user to provide their login credentials, which can be a security risk.

Personal Access Tokens (PATs): A personal access token is a form of token-based authentication that allows users to authenticate to GitHub using a token instead of a username and password. PATs can be used as a replacement for passwords and can be limited to specific actions or repositories.

OAuth 2.0: OAuth 2.0 is an open standard for authentication and authorization. It allows users to authenticate to GitHub using third-party services, such as Google or Facebook. OAuth 2.0 requires the user to grant access to the third-party application and can be used to limit access to specific resources or actions.

SSH keys: SSH keys can be used to authenticate users and applications with GitHub over the SSH protocol. SSH keys provide a secure way to authenticate without requiring the user to enter a password or personal access token.

In summary, GitHub offers several authentication methods, including username and password, personal access tokens, OAuth 2.0, and SSH keys. Each method has its own advantages and disadvantages and can be used depending on the specific use case and security requirements.

15 github commands and what are the usage of them

SETUP

1)git config --global user.name “[firstname lastname]”
set a name that is identifiable for credit when review version history

2) git config --global user.email “[valid-email]”
set an email address that will be associated with each history marker

SETUP & INIT

3)git init
initialize an existing directory as a Git repository

4)git clone [url]
retrieve an entire repository from a hosted location via URL

STAGE & SNAPSHOT

5) git status
show modified files in working directory, staged for your next commit

6) git add [file]
add a file as it looks now to your next commit (stage)

7) git commit -m “[descriptive message]”
commit your staged content as a new commit snapshot

BRANCH & MERGE

8) git branch
list your branches. a * will appear next to the currently active branch

9) git branch [branch-name]
create a new branch at the current commit

10) git merge [branch]
merge the specified branch’s history into the current one


INSPECT

11)git log
show all commits in the current branch’s history

SHARE & UPDATE

12)git merge [alias]/[branch]
merge a remote branch into your current branch to bring it up to date

13)git push [alias] [branch]
Transmit local branch commits to the remote repository branch

14)git pull
fetch and merge any commits from the tracking remote branch

TRACKING PATH CHANGES

15)git rm [file]
delete the file from project and stage the removal for commit

16)git mv [existing-path] [new-path]
change an existing file path and stage the move

17)git log --stat -M
show all commit logs with indication of any paths that moved

What are the 4 Github commands that you think you will use the most in the real project and why? 

The 4 Github commands which I think will use the most in the real project will be 

git clone
git add .
git commit -m "type a meaningful message here"
git push origin 


They are always needed to save the working files on the local drive(own laptop/desktop) process. The following of git add .
git commit -m "type a meaningful message here" and git push origin are for the updates and confirmation changes on the github platform.
The real project will able have the continue updates from other peers via the github platform which resides on the cloud which is the part
of the CI/CD development cycle. 