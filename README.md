# ansible-docker
Ansible in a Docker Container

## Get an interactive Ansible Shell
docker run -it -v /tmp/ansible:/etc/ansible u1ih/ansible




https://hub.docker.com/r/philm/ansible_playbook/dockerfile/

https://geektechstuff.com/2020/02/10/ansible-in-a-docker-container/

https://docs.ansible.com/ansible/latest/user_guide/intro_getting_started.html

ansible all -m ping -u my-ssh-username

ansible all -a "/bin/echo hello"
