# INFX 598-H In-Class Code

Fork this repo into your own account so that you can code along with me and commit/push your changes for later review.

# Pulling Updates

Periodically I will ask you to pull new commits from this original repo to pick up new directories and file stubs. 
To do this, follow the appropriate set of instructions below.

## On A Lab Machine?

The lab machines reset each time you log out, so you need to setup your environment from scratch every time:

```bash
$ git config --global user.name "your name"
$ git config --global user.email "your email"
$ git config --global core.editor nano

$ git clone <your-forked-repo-url>
$ cd infx598h-in-class

$ git remote add upstream https://github.com/drstearns/infx598h-in-class.git

$ git pull upstream master
```

The last command will typically trigger a merge commit and put you into the nano editor to confirm the commit message. Hit `ctrl+x` to exit the editor and return to the command prompt.

## On Your Own Laptop?

 If you are on your own laptop, you should do these commands only once:

```bash
$ git config --global user.name "your name"
$ git config --global user.email "your email"
$ git config --global core.editor nano

$ git clone <your-forked-repo-url>
$ cd infx598h-in-class

$ git remote add upstream https://github.com/drstearns/infx598h-in-class.git
```

Then each time you need to pull from the my original repo, run these commands:

```bash
# change into your local repo directory
$ cd infx598h-in-class

# check for any uncommitted changes
# and commit if necessary
$ git status

# pull new commits from the upstream repo
$ git pull upstream master
```
