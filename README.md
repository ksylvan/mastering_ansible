# mastering_ansible

Ansible Course by Chris Lunsford from Udemy

https://www.udemy.com/mastering-ansible/learn/v4/overview

I used `virt-manager` on Fedora to spin up the 5 needed Ubuntu 14.04
hosts, then set up the ssh keys to start playing with ansible on the
control host.

The `bin/hosts` script uses the `virsh` command to generate the list
of hosts in `/etc/hosts` format (so you can simply append it to the
hosts file in your control host).
