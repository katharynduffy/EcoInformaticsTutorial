:octocat:
# Using GitHub to Make Your Life a Whole Lot Easier  :+1:




# The Basics




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
