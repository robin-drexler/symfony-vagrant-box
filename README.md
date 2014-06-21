# CAUTION: WIP

# What?
Vagrant box to get symfony projects up and running for local development.
Current Setup:

 * Ubuntu 12.04
 * php 5.3
 * mysql
 * apache2

# Prerequisites

Have [vagrant](http://www.vagrantup.com/) and [ansible](http://www.ansible.com/home) installed.

# How to use it

 * Clone this repo
```bash
$ git clone git@bitbucket.org:rocgame/symfony-vagrant
```
 * Checkout / install your symfony app in a subfolder
 * Start vagrant box 
```bash
 $ vagrant up
```
 * visit your site 
```
 http://localhost:8080/{subfolder}/web/config.php
```

# Data
## Mysql
 * User: symfony
 * Password: symfony

# Known ToDos
 - [ ] Mail Sending
