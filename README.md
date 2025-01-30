# role-junos-health-checks
Ansible role to perform health-checks on junos devices

# How to use

Step 1: Install the role in your environment.
   - You could have roles/requirements.yml if running on AAP.
   - Or simple install on your environment.

Step 2: Define your variables. See example-vars.yml

Step 3: Call the role from your playbook. See example-playboo.vars

# Example

## example playbook
example-playbook.yml

## Notes
- Role extracts the running configuration and dumps them on a file in the local disk.
- Tasks have to be included to send this file somewhere e.g git repo or to an artifacts store.
