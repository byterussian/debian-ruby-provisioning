# Creates a Ruby Env in Debian based distros

Before to use:

- In `group_vars/all` insert your ssh-public-key and the ruby version you want to install

- Specify your host/s in the inventory file `staging` 

- (Optional) Run `ansible-playbook -s bootstrap.yml -i staging` to create ruby user and little server hardening

- Run `ansible-playbook -vvvv -s ruby.yml -i staging`

If you want to try the provisioning in your local machine make sure you have installed Vagrant then run `vagrant up` in project dir.
