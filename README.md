# Ansible projects



* [Playbooks](https://github.com/ihavelapki/ansible/tree/main/playbooks)
	* [Add user](https://github.com/ihavelapki/ansible/blob/main/playbooks/adduser.yml)
	* [Install docker](https://github.com/ihavelapki/ansible/blob/main/playbooks/install_docker.yml)
* [Run commands](#run_commands)


## Run commands
<a id="run_commands"></a>

```sh
ansible-playbook -i inventories/inventory.ini -l kek02 playbooks/adduser.yml -e "@variables/userparams.yml" -v
```