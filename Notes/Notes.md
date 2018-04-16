Notes - Monday 16th April 2018

** To do **
    Watch the videos about user centric. 5 videos : one a day for next monday (23/04/18)

** Bash command **
    pwd     == Print Working Directory (enable to know where we are)
    ls      == list files of the current directory
    touch   == create a new file. touch + file name
    rm      == remove file. rm + file name
    cd      == change directory.
    cd ..   == getting in the file above (root)
    cd ../..== getting two files above 
    mkdir   == create directory
    rmdir   == remove (delete) directory. We have to be in the directory containing the directory we want to delete.
    rm -rf  == remove directory and all files in the directory
                r stands for "recursive" : do that for all files beneath
                f stands for force (without asking, just do it)
                rm -rf /    delete everything on your computer
    quit nano editor : ctrl + x 
    
    The whole procedure to create a repository on Git (or another host) and link the local repository to it :
    
    git init (create a git repository locally)
    git status
    git add filename (use . for everything at the root) to add a file to the local git repository
    git commit -m "Initial commit" (the message between the " " are for us, developers)
    
    Everytime we commit, we need to first "git add filename" and then "git commit -m "customize message".
    You need to provide a message, Git force you to do so. This message is adress to "us", for our own reading.
    
    git remote add origin git@github.com:Xorast/hello-world.git  Create a remote repository, and name the local git "origin" (convention) and 
    link it to the repository that is at the following adress : "git@github.com:Xorast...". The latter (on Github) will be the "master"
    git push -u origin master (git push -u : upload : origin : from "origin"; the local git; to the branch "master" (in that instance)
    
    git push 
    
    You MUST commit BEFORE you PUSH !!
    
    ONCE the local git created, then; to maintain :
    
    git add filename (or .)  if there is no file in a folder then it's not added. All files must be added, the sync is not based on folder. Best thing : use "."
    git commit -m "..." (to commit locally)
    git push (to sync with the remote repository)
    

** Shorcut **
    ctrl + /     comments
    
** vocabulary **
    Directory and folder are the exact same thing.
    
** Notes **
    We try to avoid to use absolute path in coding because if one root file changes then everything fall down.
    We tend to use relative path. We use " ./lalalala" the "./" is "in the directory we are currently in". For example for the link to the css file for html.
    One dot . directory we are in
    Two dot .. directory one level above
    
    Commit is like saving and Pushing is putting on the cloud.
    Commit is local and push in to push to a distance host.
    Take the habit to commit often ! Important for employer; show how you got to the final result.
    
    
    
    
    
    

