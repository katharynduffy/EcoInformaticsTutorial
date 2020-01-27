
# Using GitHub to Make Your Life a Whole Lot Easier  :+1:


# Introduction
* Git versus GitHub
![git vs. github](/Users/kdw223/Research/PostDoc/EcoInformaticsTutorial/images/Gitvs.Github-1a.jpg)

# How does Git work?
http://onlywei.github.io/explain-git-with-d3/#commit

# The Basics
1. Git init a repo
2. Clone a repo onto your own machine
3. Make changes on your own machine
  * save and push to :octocat:





# Ignoring folders (like ones that are too big) via a .gitignore file:

## ignore all .a files
*.a

## but do track lib.a, even though you're ignoring .a files above
!lib.a

## only ignore the TODO file in the current directory, not subdir/TODO
/TODO

## ignore all files in any directory named build
build/

## ignore doc/notes.txt, but not doc/server/arch.txt
doc/*.txt

## ignore all .pdf files in the doc/ directory and any of its subdirectories
doc/**/*.pdf
