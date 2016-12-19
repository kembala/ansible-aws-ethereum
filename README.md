## ansible-aws-ethereum
Ansible playbooks to launch an Ethereum Private Network on AWS infrastructure.

## HOW
- Git clone this repo.
- Edit the configuration in `vars/config.yml` and in `ansible.cfg` if necessary.
- Export your AWS keys (or add the commands to your .profile or .bashrc)
    - `export AWS_SECRET_ACCESS_KEY='###'` 
    - `export AWS_ACCESS_KEY_ID='###'`
- Run it
    - `ansible-playbook -i inventory/ec2.py geth.yml`
