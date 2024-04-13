# Ansible projects



* [Playbooks](https://github.com/ihavelapki/ansible/tree/main/playbooks)
	* [Adduser](https://github.com/ihavelapki/ansible/blob/main/playbooks/adduser.yml)
* [Run commands](#run_commands)


## Run commands
<a id="run_commands"></a>

```sh
ansible-playbook -i inventories/inventory.ini -l kek02 playbooks/adduser.yml -e "@variables/userparams.yml" -v
```