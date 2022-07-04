# Module 3 Home work

### Initializing project folder
- mkdir module3
- git init
- git add README.md
- echo "# Module 3 Home work" > README.md
- git add README.md
- git commit -m "My 1 commit onto master"
- git remote add origin - git@- github.com:etursunbaev/python-module3.- git
- git remote --v
- git push -u origin master
- git checkout -b develop
- nano README.md
- git status
- git log
- git commit -m "My 2 commit onto develop"
- git push origin develop

### Branching out 
- cd ../
- git clone - git@- github.com:etursunbaev/python-module3.- git
- cd python-module3/
- git status
- git log
- git checkout develop
- git log
- git checkout -b branch-1
- nano example.txt
- git status
- git add .
- git status
- git commit -m "My 3 commit onto branch-1"
- git push origin branch-1
- git checkout develop
- git checkout -b branch-2
- nano example.txt
- git add .
- git commit -m "My 4 commit into branch-2"
- git push origin branch-2

### Merging and resolving

#### - git merge approach
- git checkout develop
- git pull origin develop
- git merge branch-1
- git log
- git status

#### - git rebase approach
- git rebase branch-2 develop
- git status
- nano example.txt
- git status
- git log
- git add example.txt
- git status
- git rebase --continue
- git status
- git push -f origin develop
