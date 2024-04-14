# Ansible projects



* [Playbooks](https://github.com/ihavelapki/ansible/tree/main/playbooks)
	* [Add user](https://github.com/ihavelapki/ansible/blob/main/playbooks/adduser.yml)
	* [Install docker](https://github.com/ihavelapki/ansible/blob/main/playbooks/install_docker.yml)
* [Run commands](#run_commands)


## Run commands
<a id="run_commands"></a>

### Run docker install playbook:
```sh
ansible-playbook -i inventories/inventory.ini -l kek02 playbooks/install_docker.yml --ask-become-pass -v -C
```

### Run creation new user playbook:
```sh
ansible-playbook -i inventories/inventory.ini -l kek02 playbooks/adduser.yml -e "@variables/user_params.yml" --ask-become-pass -v -C
```