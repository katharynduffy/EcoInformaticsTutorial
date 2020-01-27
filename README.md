
# Using GitHub to Make Your Life a Whole Lot Easier  :+1:
----
![](http://www.phdcomics.com/)

![](https://bids.github.io/2015-06-04-berkeley/git/fig/play-changes.svg)

# Introduction
* Git versus GitHub


![git vs. github](https://blog.devmountain.com/wp-content/uploads/2019/07/Gitvs.Github-1a.jpg)

# How does Git work?
http://onlywei.github.io/explain-git-with-d3/#commit

# Hands on Basics
1. Git init a repo
2. Clone a repo onto your own machine
3. Make changes on your own machine
4. Save and push to GitHub :octocat:

# Collaborating with Others on GitHub

1. Generally you submit a pull request to a repo that someone else manages
```
git push origin master
```


2.  But if you are both frequently pushing/pulling *and you trust this person to not constantly break your code* you can add collaborators so that you can avoid pull requests

# How to be a good collaborator (and just good rules in general)

1. Use commit messages that make sense
2. Push often, push always
3. Develop on a dev branch, keep your master branch deployable



![git out](https://rafikitechnology.files.wordpress.com/2019/07/git-emergency-procedure.png)

# But what happens if you mess up?  
(E.g. you forget to push or you are editing the same chunk of your code as a collaborator)

![](http://swcarpentry.github.io/git-novice/fig/conflict.svg)


# A Few More Basics


## Ignoring folders (like ones that are too big or have your passwords) via a .gitignore file:

 ignore all .a files
```
*.a
```
 but do track lib.a, even though you're ignoring .a files above
```
!lib.a
```
 only ignore the TODO file in the current directory, not subdir/TODO
```
/TODO
```
 ignore all files in any directory named build
```
build/
```
 ignore doc/notes.txt, but not doc/server/arch.txt
```
doc/*.txt
```
 ignore all .pdf files in the doc/ directory and any of its subdirectories
```
*.pdf
```
## What to do when everything goes south....

Erase mistakes and craft replacement history
```
$ git reset [commit]
```
Undoes all commits after [commit], preserving changes locally
```
$ git reset --hard [commit]
```

if you're not sure?
```
git stash
git pulling
```

and when you've decided that you just should have stayed in bed today and not broken your entire code/app

```
git reset --hard HEAD
```
