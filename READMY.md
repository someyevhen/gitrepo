### ansible playbook for docker install on centos7
* go to a dir with the playbook
> cd /etc/ansible
* run the playbook
> ansible-playbook docker.yml

to ferify docker service status run the following command on remote host
> systemctl status docker
