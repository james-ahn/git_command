#git set the name pw 

 git config --global user.name "name"
 git config --global user.email "email@gmail.com"
 
 
#git aliases

git config --global alias.st status
git config --global alias.l "log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short"
git config --global alias.ch checkout
git config --global alias.cm commit
git config --global alias.br branch
git config --global alias.cam "commit -a -m"
