# Puppet Facts

## How to retrieve facts

You can gather facts about a remote hosts by using the facter command.

In puppet, the facts consists of:
* core facts, defined by Puppet
* custom and external facts, defined in the modules created by the user

If you want to gather all the facts you can run the following command after logging on the remote hosts: 

   ```
   sudo /opt/puppetlabs/bin/facter -p
   ```

More infos about the facter tool can be found [here](https://puppet.com/docs/puppet/latest/facter.html).

## Facts list

Go to the [facts.json](facts.json) file to see the latest available facts provided by Puppet.
