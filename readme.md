# Fale's workstations Ansible Repository

## First run
First you need to add the host key

    ssh IP 

Then is possible to do the basic setup

    ansible-playbook playbooks/firstrun.yml -uroot -k -lIP

## Following runs

    ansible-playbook PLAYBOOK.yml
