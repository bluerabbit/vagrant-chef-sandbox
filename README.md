vagrant-chef-sandbox
====================

## gem install


```
gem install vagrant
gem install vagrantboxes
gem install vagrant-vbguest
gem install sahara
gem install chef
gem install knife-solo
gem install berkshelf
```


## VirtualBox

- https://www.virtualbox.org/wiki/Downloads

## Vagrant

- gem install vagrant
- vagrant box add ubuntu http://cloud-images.ubuntu.com/quantal/current/quantal-server-cloudimg-vagrant-amd64-disk1.box
 - http://www.vagrantbox.es/
- vagrant init ubuntu

- vagrant up
 - server start
- vagrant ssh
 - ssh
- vagrant reload
 - reboot
- vagrant halt
 - shutdown
- vagrant destroy ubuntu
- vagrant ssh-config

## sahara
- vagrant gem install sahara
- vagrant sandbox on
- vagrant sandbox rollback
- vagrant sandbox commit

## knife-solo
- bundle exec vagrant provision
