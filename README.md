#dotfile 使用规则
```
cd ~/  
rm -rf .vimrc .zshrc #首先删除自身机器上原有的dotfiles 
mv .vimrc ~/dotfile/.vimrc  
mv .zshrc  ~/dotfiles/.zshrc  
ln -s ~/dotfiles/.vimrc .vimrc  
ln -s ~/dotfiles/.zshrc .zshrc
```

可以看出核心便是软连接
