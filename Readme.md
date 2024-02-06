1  clear
    2  apt-get update -y
    3  clear
    4  mkdir Assignment1
    5  cd Assignment1
    6  clear
    7  touch Code.txt Log.txt Output.txt
    8  git add Code.txt Output.txt
    9  git init
   10  clear
   11  ls
   12  git add Code.txt Output.txt
   13  git status
   14  git commit -m "Adding these two files to master branch"
   15  git config --global user.name "hariagre"
   16  git config --global user.email "hariagre@gmail.com"
   17  git commit --amend --reset-author
   18  git log
   19  git remote add origin https://github.com/hariagre/AllAssignments.git
   20  git push -u origin master
