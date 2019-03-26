Role Name
=========
ssh-access

1.Inventories are in /etc/ansible/hosts
2. User name : chandu (hard coded.. trying to get from user as an input by using vars_prompt)
3. I was testd with root user. root public key has been copied into /etc/ansible/user_ssh_keys/chandu
4. use ansible-playbook -e "action=grant" site.yml for user cretion and key authendication
5 use ansible-playbook -e "action=revoke" site.yml for user deletion and revoke key
