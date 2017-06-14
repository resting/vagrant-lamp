# How to use
1. Install [Vagrant](https://www.vagrantup.com/docs/installation/)
2. Put `Vagrantfile` in a folder
3. `vagrant up`

# To expose MYSQL
1. `vagrant ssh`
2. `/vagrant/update-mysqld.cnf.sh`
3. Enter `root` when prompted for password
4. Connect from host with `127.0.0.1:3309`

# Set ubuntu password
1. `sudo passwd ubuntu`
2. Set password