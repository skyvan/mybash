mybash
======

sync my bashrc and bash_profile to all machines

## install git rpm first
##Make sure git rpm is already installed
sudo yum install git

##backup original bash files in home directory

mv all bash files in home to backup directory first.

## clone the git repo to home
git clone https://github.com/skydome/mybash ~/.mybash

## create links to the bash files in mybash
ln -s ~/.mybash/bashrc ~/.bashrc
ln -s ~/.mybash/bash_profile ~/.bash_profile
ln -s ~/.mybash/bash_logout ~/.bash_logout


##end
