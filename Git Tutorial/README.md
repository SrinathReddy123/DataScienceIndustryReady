This project is created to have a better understanding of github and how it is actually used in an organisation.

As part of this project, we have achieved below things.

1.Demonstarted basic git commands with explanation and screenshots
  1.Configure Name
  set your name  so that the commits can associate with your user account.

  git config --global user.name "username"
  
  <img width="322" alt="1 GitConfigName" src="https://user-images.githubusercontent.com/90196559/195888763-db03a8e7-17df-4e77-8859-f35e997d6123.png">
  
 2.Configure Email
  set your email so that the commits can associate with your user account.

  git config --global user.email "email@example.com"
  
  <img width="521" alt="2 GitConfigEmail" src="https://user-images.githubusercontent.com/90196559/195888867-b6bc7767-27eb-4aab-80c6-dcec7ec961af.png">
  
  3.Git Status
  Shows information about the current changes ( new files added, updated, deleted, renamed etc)
   used to keep track of all all changes that are made on the files of current working directory.
   
    git status
   
   <img width="419" alt="3 GitStatus" src="https://user-images.githubusercontent.com/90196559/195888965-1fa19321-ce2a-412e-8d2e-c91c38eae1df.png">
   
  4.Git Add
   Before we commit we should add all changes to staging.
   Adds all the current changes to the staging area.


   Adds the file/files to the git index(called staging index).Before we make a commit to git, it's  necessary to add the files t othe git staging.

   Adding multiple files: git add file1 file2 file3

   To add all files in the current directory:
   git add .   
   
   <img width="305" alt="4 GitAdd" src="https://user-images.githubusercontent.com/90196559/195889031-55b8b26f-a408-4240-a5b4-22f5f2a15a44.png">
   
   5.Git Commit
  To make a commit - it means save the current index(staging) as a snapshot and commit it to project history. It is always advised to provide a proper message along with a commit for easier undrstanding.

  git commit -m "our descriptive message for the commit"

  git commit --amend:
  If you want to modify your most recent commit,use the amend command. It lets you modify the log message and also the files in the commit.

  
  git commit --am "your message":
  If you want to add and commit in 1 shot, use the -a flag. It automatically stages all  the modified and deleted files and commits them as well.
  
  <img width="355" alt="5 GitCommit" src="https://user-images.githubusercontent.com/90196559/195889112-b03c0763-5ca7-4ced-bcb8-147355876b36.png">

   6.Git Push
    Push all the commits in your branch to the remote branch.
    Push the changes in the staging area to the remote main branch in Git. 
    We can replace the main branch with any other branch name.
    
    <img width="442" alt="6 GitPush" src="https://user-images.githubusercontent.com/90196559/195889190-ca201a6a-87f8-41fd-9a91-1485e49d3693.png">
  
   7.Git Pull
   Pull commits from the remote branch into your local branch.
   Fetches and pulls the changes from the remote repository in Git to our local branch.
   
   <img width="250" alt="7 GitPull" src="https://user-images.githubusercontent.com/90196559/195889296-d6bd1600-c154-4c8b-88a2-7aa27e9da6ac.png">

  8.Git Fetch:
  Updates the repository by downloading the objects and refs.

  git push
  
  <img width="344" alt="8 GitFetch" src="https://user-images.githubusercontent.com/90196559/195889384-b20953bb-b194-4ab5-9a83-5c6bbedeb159.png">
  
  9.Git Branch:
  In Git whenever you want to work on something, instead of doing it on the main branch, we create a new branch and work on this branch.
  We never work on the master branches.

  To create a new branch:
    git branch branchname
  To checkout to the branch:
    git checkout branchname     

  To create and checkout in one command:
    git checkout --b branchname or 
    git switch branchname

  To show a list of all branches in our repository along with current branch(green color):
    git branch --list      

  To delete local branch:
    git branch --d branchname 

  To delete remote branch:  
    git push origin --d remotebranchname   
    
    <img width="371" alt="9 GitBranch" src="https://user-images.githubusercontent.com/90196559/195889485-de588775-784d-4283-965b-b4a876bc3c62.png">
    
  10.Other Branch commands:
  git branch -d srinath
  
  <img width="298" alt="10 GitBranchDelete" src="https://user-images.githubusercontent.com/90196559/195889568-4fe094f6-31b7-4993-b282-fc4ce546338e.png">

  11.Git Merge
  Merge changes/commits from a specified branch into the current branch.

  git merge specifiedbranchname
  
  <img width="319" alt="11 GitMerge" src="https://user-images.githubusercontent.com/90196559/195889670-d6c98d9e-b184-40e6-ad9d-1ea40ba2a35b.png">
  
  12.Git log
  view the entire commit history for the current branch.

  git log

  git log --oneline
  Very much readable as it displays only one commit per line in terminal

 <img width="518" alt="12 Git Log" src="https://user-images.githubusercontent.com/90196559/195889785-98e44508-47da-437a-9772-d99725e4c512.png">
 
   13. Git Diff:
    view changes between staged files and current working directory.

    git diff
    
    <img width="298" alt="13 Git Diff" src="https://user-images.githubusercontent.com/90196559/195889858-2e2b802d-e9a8-407c-a406-acc74ee7d151.png">

   14.Git clone
    clones 1 copy other's git repository in our local repository
    (Clones the repository to the local machine.
    git clone <repository_url>
    
   15. Git Stash
     use the stash command to temporarily save your work without committing.

     git stash

     view all stashes:
     git stash list 
     
     <img width="473" alt="15 Git stash" src="https://user-images.githubusercontent.com/90196559/195889970-ccefe002-c417-4418-9d98-7662144c0a6c.png">


2.Created this project as an open-source project.


3.Added one collaborator.
