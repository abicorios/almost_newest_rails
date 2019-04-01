# almost_newest_rails
Auto up dev env for rails
# dependencies
Virtualbox, Vagrant, git
# instalation
```
git clone https://github.com/abicorios/almost_newest_rails
cd almost_newest_rails
vagrant up
vagrant ssh
```
# new blog
```
rails new blog
cd blog
bin/rails server -b 0.0.0.0
```
# see blog
Open `192.168.33.8:3000` in browser
# stop
Press `Ctrl+C` in console
# exit
```
exit
```
# halt
```
vagrant halt
```
# destroy
```
vagrant destroy -f
```
# refs
https://github.com/creationix/nvm

https://rvm.io/integration/vagrant
