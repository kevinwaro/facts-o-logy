# Ansible Facts

## How to retrieve facts

You can gather facts about a remote hosts by using the setup module. This module is usually automatically called by playbooks.
It can also be used with the standalone /usr/bin/ansible command:

   ```
   ansible -i <INVENTORY> <HOST> -m setup 
   ```

More infos about the setup module can be found [here](http://https://docs.ansible.com/ansible/latest/modules/setup_module.html).

## Facts list

Go to the [facts.json](facts.json) file to see the latest available facts provided by Ansible.
