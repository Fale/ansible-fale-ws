# Fale's workstations Ansible Repository

## First run
First you need to add the host key

    ssh IP 

Then is possible to do the basic setup

    ansible-playbook playbooks/firstrun.yml -uroot -k -lIP

## Following runs

    ansible-playbook PLAYBOOK.yml

## First run on local machines
In this case, execute those two commands before anything else

    dnf install -y ansible git sshpass
    git clone https://github.com/Fale/ansible-fale-ws.git

and ensure that the proper SSH keys are installed properly
