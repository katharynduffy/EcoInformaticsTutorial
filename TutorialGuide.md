
# Using GitHub to Make Your Life a Whole Lot Easier  :+1:


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


![git out](https://www.google.com/imgres?imgurl=https%3A%2F%2Fpbs.twimg.com%2Fmedia%2FCqzJkJ_VYAA5CtM.jpg&imgrefurl=https%3A%2F%2Ftwitter.com%2Fsmartertools%2Fstatus%2F769211721386827776&docid=89hBZUsfY4GbIM&tbnid=WtMhfZ4lCFHs2M%3A&vet=10ahUKEwjbqYOUl6TnAhV9HDQIHcuMB24QMwhTKAUwBQ..i&w=440&h=441&bih=920&biw=1920&q=git%20push%20git%20out%20fire&ved=0ahUKEwjbqYOUl6TnAhV9HDQIHcuMB24QMwhTKAUwBQ&iact=mrc&uact=8)



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
