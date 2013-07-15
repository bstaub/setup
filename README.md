setup.git
=========
Clone and run this on a new EC2 instance running Ubuntu 12.04.2 LTS to
configure both the machine and your individual development environment as
follows:

```sh
cd $HOME
sudo apt-get install -y git-core
git clone https://github.com/bstaub/setup.git
./setup/setup.sh   
```


setup heroku
============

```sh
wget -qO- https://toolbelt.heroku.com/install-ubuntu.sh | sh
which git
which heroku
heroku login
heroku keys:add
heroku create
git push heroku master
```


git push some content
=====================

```sh
git add filexy.txt
git commit -m "first commit"
git push -u origin master
```









See also http://github.com/startup-class/dotfiles and
[Startup Engineering Video Lectures 4a/4b](https://class.coursera.org/startup-001/lecture/index)
for more details.





