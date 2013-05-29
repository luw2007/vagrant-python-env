**Table of Contents**

- [Overview](#overview)
- [Workstation Setup](#workstation-setup)
- [Usage](#usage)
- [TODO](#todo)
- [LINKS](#useful-links)


Overview
========
This is a sample repo for spinning up a python dev vm. I use [Vagrant][vagrant], [berkshelf][berks], [chef solo][cs] and [Virtualbox][vbox] make a virtual machine with vim, git, pip.

[vagrant]: http://www.vagrantup.com
[berks]: http://berkshelf.com/
[cs]: http://wiki.opscode.com/display/chef/Chef+Solo
[vbox]: https://www.virtualbox.org


Workstation Setup
=================
- ruby and gem (apt-get install rubygems, or yum, pacman )

- Virtualbox [Official download](https://www.virtualbox.org/wiki/Downloads)
- ruby and gem (apt-get install rubygems, or yum, pacman )
- vagrant (gem install vagrant)
- berkshelf (gem install berkshelf)

Usage
=====
>
    $ git clone  https://github.com/luw2007/vagrant-python-env.git
    $ cd vagrant-python-env
    $ berks install --path cookbooks
    $ vagrant up
    $ vagrant ssh

TODO
====
- add some usefull python-packages

LINKS
======

http://wiki.opscode.com/display/chef/Shef
http://docs.vagrantup.com/v1/docs/provisioners/chef_solo.html
