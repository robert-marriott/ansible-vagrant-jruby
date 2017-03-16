# ansible-vagrant-jruby
Ansible playbook and vagrantfile to create a standard CentOS 6.8 box

## Procedure

### Initialize standard centos 6.8 image
```
$ vagrant up
```
Running vagrant will call ansible during its provisioning process. Without the cert, it will need to be on guestwifi or a home network. If you need to reprovision once it is up:
```
$ vagrant provision
```

### Todo:
 [] Add booz self signed cert for wifi-net
