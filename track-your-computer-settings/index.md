# Create a Repo to Track Your Computer's Settings


As a beginner, I manually add several dotfiles to the Github repo like this.

```shell
# Create a Repo
git clone git@github.com:<username>/dotfiles.git
cd dotfiles
mv ~/.vimrc .
git add .vimrc
git commit -m "your message"
 
# Symbolically linking files
ln -s /path/to/dotfiles/.vimrc ~/.vimrc
 
# push to remote
git push origin master
```

References:
Some tutorials : [Guide to dotfiles on Github](https://dotfiles.github.io/)

