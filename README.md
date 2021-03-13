 OpenSSH Server
==============

Ansible role to configure the OpenSSH `ssh` server.

# Deprecation warning
These roles here have some changes that are not backwards compatible and have therefore moved to this git repository:
[github.com/roles-ansible/ansible_role_sshd](https://github.com/roles-ansible/ansible_role_sshd.git)


Please have a look at the new syntax of the variables and use it there.

If you used this role without any config changes, than it is fully compatible!

 combinations
---------------
It is highly recomended to use this role together with a role to manage users and to manage the sshd configuration.<br/>
The following roles are tested in combination and work well - at least for the user [DO1JLR](https://github.com/do1jlr):
 - [github.com/chaos-bodensee/role-manage_users](https://github.com/chaos-bodensee/role-manage_users.git)
 - [github.com/chaos-bodensee/role-ssh_authorized_keys](https://github.com/chaos-bodensee/role-ssh_authorized_keys.git)
 - [https://github.com/roles-ansible/ansible_role_sshd](https://github.com/roles-ansible/ansible_role_sshd) *(the new one)*
