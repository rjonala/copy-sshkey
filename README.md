Ansible role to copy SSH Public Key from Ansible host to remote machines for passwordless authentication.

    ansible-playbook -i /tmp/ansible-workspace/environments/QA/inventory --extra-vars "host=QA" --ask-pass --ask-become-pass main.yml
