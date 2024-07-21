
comandes we just use it

##git add * or the name of the file
##git status
##git commit -m "description"
##mkdir 
create directory
##rmdir 
clear the directory
##rm 
remove a file
##touch 
creat a file 
##ls 
browse the files
##git branch 
(get you what branch you are working on)
##git remote -v 
(get you the gitub origin)
##git push origin main 
(export the changes to github)
##git pull origin  
(to get changes from the github to your local)
##git config --list or -l
(get you the all configuration)
##git config -- user.name 
(use this comande to see the config name)
##git config --user.name "you can change the name user
"
##git config --show origin 
(to see the soure of all the configration)
##git config --global --unset user.name 
(to delete the userName)
##git config --global --edit 
(the gui config)
##ssh-keygen -t rsa -b 4094 -C "hamidnba06@gmail.com"
(to generate the ssh public key)
##cat ~/.ssh/id_rsa.pub
(to get the public key from the file on your pc)
##ssh -T git@github.com 
(command to test the ssh key)
##git init 
(this comande create a git repository)
##git remote add origin https://github.com/Deramchi-A/new.git(to add repository from the local and push it to github)
##git push -u origin master or main
(get it from git status)
1-Create a file:
with open ("test.txt",'w') as fp:
    fp.write('new line')
2-Read a file:
with open ("test.txt",'r') as fp:
    fp.read()
3-Rename and remove a file :
 os.rename('old name','new name')
 os.remove('file path')
4-Copy and move a file:
 shutil.copy('src file path','new path')
 shutil.move('src file path','new path')
5-Working with directories:
 os.listdir('dir path') #Get all files.
 shutil.rmtree('dir path')
 shutil.copytree('src path','dist path') #copy dir
