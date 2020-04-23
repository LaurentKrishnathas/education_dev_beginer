Linux basic commands:
  mkdir -p ~/gits/test_lesson1
  cd ~/gits/test_lesson1
  rm test.txt   
  tree
  pwd
  find . -name "lk*"

Creating git folder and commiting:
  git init
  echo "test">test.txt
  cat test.txt
  git add test.txt
  git commit -m"first commit"


Creating git branch:
  git branch --help
  git branch tmp
  git checkout tmp
  git status
  touch test2.txt
  echo "one">>test2.txt
  echo "two">>text2.txt
  cat text2.txt
  echo "three">test2.txt
  cat text2.txt
  
  
Deleting and recovering files:
  rm text2.txt
  git checkout text2.txt

Remote repository:
  git clone
  git pull
  git push



Gradle:
  gradle init
  gradle run
  
  
