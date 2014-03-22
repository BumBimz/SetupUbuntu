SetupUbuntu
===========
PHP5.5
======
 sudo add-apt-repository ppa:ondrej/php5
 sudo apt-get update
 sudo apt-get install python-software-properties
 sudo apt-get update
 sudo apt-get install php5
 
PHPUnit
=======
 Download composer.json & composer.phar
 php composer.phar install

RubyGem
=======
 sudo apt-get install rubygems
Watchr
======
 sudo gem install watchr
 Download watchr.rb

SETPATH
=======
 add 'PATH=$PATH:~/vendor/bin;export PATH;' to .bashrc

Curl
====
sudo apt-get install curl

VIM
===
 sudo apt-get install vim

GIT
===
 sudo apt-get install git-core

Rake
====
sudo apt-get install rake


Vim Plugin Janus
================
 curl -Lo- https://bit.ly/janus-bootstrap | bash
 /.vim/janus/vim/core/before/plugin/settings.vim

SETGIT
======
 cd ~/.ssh
 ssh-keygen -t rsa -C "your_email@example.com"
 ssh-add id_rsa
 copy ~/.ssh/id_rsa.pub =>https://github.com/settings/ssh
 
wiless dell
===========
sudo apt-get update
sudo apt-get install bcmwl-kernel-source
