# A very first step gittest of Mr.AUNG PYAE
I am on Fedora25.
First,We must install Git on ur local computer.
#dnf -y install git 
and you add your git account to ur local computer.Commands are: 
#git config --global user.email "aungpyae89@gmail.com"       #change with ur github user email
#git config --global user.name "aungpyae89"                    #change with ur username 
then make a directory in ur local computer. 
#mkdir gittest   ("gittest" might be ur reponame)
Change Directory into this directory.
#cd gittest 
then  go to your github page on https://github.com and sign in then create a new project (repo) 
I gave  a name same as my directory , "gittest" and write description about your project.
then u can see ur new repo and u will get a link of ur repo and example commands.So let go back to terminal again ,
Now we will create readme.md file.  
#echo "# A very first step gittest of Mr.AUNG PYAE" >> README.md     (">>" means append to README.md file "here is ur readme note")
then u can check with ls command  and u see README.md file 
#ls 
then type (for git repo starting).
#git init
#git add README.md     (add README file)
#git commit -m "Very first Commit"   (this one is store in the head not yet going to remote server) 
then 
#git remote add origin https://github.com/aungpyae89/gittest-.git    (remote add to our server or github page) 
#git push -u origin master   (push as master to ur remote repo) 
its will ask you username and password of ur github.
refresh or press ur new repo page on github.com u can see ur README.md file.
You can add more files or data same as  this way. 

"Thanks"
./Aung Pyae./
