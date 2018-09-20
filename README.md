
# My Bashrc profile


You can add it to your system and modify it as you like, or if you want you can report issues here to make it fancier 

Make it work as follows:

```bash
cd bashrc/
mv ~/.bashrc ~/.bashrc.old
ln -s $PWD/bashrc ~/bashrc/.bashrc 
ln -s $PWD/bash_alias ~/.bash_alias
ln -s $PWD/git-prompt.sh ~/.git-prompt.sh
source ~/.bashrc
```

Then you will have a colorfull bash prompt.

##Changelog

added cowsay for a cheerup message.



This is a modification of the original source:
http://mediadoneright.com/content/ultimate-git-ps1-bash-prompt
And i dont want it to be lost on the vast internet
