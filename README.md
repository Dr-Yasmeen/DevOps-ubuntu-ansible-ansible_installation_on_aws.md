# DevOps-ubuntu-ansible-ansible_installation_on_aws.md
DevOps/ubuntu/ansible/ansible_installation_on_aws.md
# +++++ ANSIBLE INSTALLATION +++++


#### Update Ubuntu packages
```
$ sudo -i
$ apt-get update
```

<br />

#### Change hostname
```
$ hostnamectl set-hostname ansible
$ bash
$ hostname
```

<br />

#### Check Ansible exist or not ?
```
$ ansible --version
```

<br />

#### Add Ansible repository
```
$ sudo apt-add-repository ppa:ansible/ansible
```

<br />

#### Now fetch latest update & install Ansible
```
$ sudo apt update
$ sudo apt-get install ansible
```

<br />

#### Now check Ansible version
```
$ ansible --version
```



## `*************************   EOF   *************************`
