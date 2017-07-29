#Git Basic commands 

 $ git init

 $ git add [file name]


##config user

 $ git config --global user.name ""
 $ git config --global user.email "" 


 $ git commit -a (In vi editor enable , press i and add description , press Esc and :wq!)


##Create Branch

 $ git checkout -b [Branch Name]

##Change branch 

 $ git checkout [Branch Name] 


##Merge Branch

 $ git merge [Branch Name]


##Add Remote URL to local repo

 git remote add origin [Origin URL]
 
 
#Clone existing project

 $ git clone [Origin URL] [ dir name ]
 

#Fetch branch(s) 
 
 Fetch single branches
  
  $ git fetch origin [Branch Name]
 
  $ git checkout [Branch Name]
 
 To make sure all the things are updated in your local
 
  $ git pull origin [Fetched Branch name]
  
To check existing branches
  
  $ git branch
 
 ##Clone specific branch  on to local
 
 $ git clone -b[Branch name] [Origin URL] [ dir name ]
 
 To check existing branches
  
  $ git branch
 







