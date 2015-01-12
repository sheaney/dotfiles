dotfiles.git
============
Clone and run this on a new EC2 instance running Ubuntu to
configure your `bash` development environment as follows:

```sh
cd $HOME
git clone https://github.com/sheaney/dotfiles.git
ln -sb dotfiles/.bash_profile .
ln -sb dotfiles/.bashrc .
ln -sb dotfiles/.bashrc_custom .
```
