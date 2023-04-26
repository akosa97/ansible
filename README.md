Installed Ansible: You installed Ansible on your local machine using the appropriate package manager or installation script for your operating system.

Created an Inventory File: You created an inventory file named /etc/ansible/hosts that contains a list of IP addresses or hostnames of the remote servers you want to manage with Ansible.
![ansible installed, host folder](https://user-images.githubusercontent.com/91312467/234473204-cc378964-536c-4d63-b700-a89698e93d05.jpg)

Defined Server Configuration: Defined the server configuration for each of the remote servers in the inventory file. This includes information such as the server's IP address, username, and SSH private key location.
![added IP addresses into hosts file](https://user-images.githubusercontent.com/91312467/234472210-1a016d5f-edeb-49f0-b2dc-e90902ea3ef5.jpg)

Checked Server Connection: Tested the connection to the remote servers using the ansible command with the ping module to ensure that Ansible can communicate with each of the servers in the inventory file.
![all ansible servers running](https://user-images.githubusercontent.com/91312467/234472349-2c9ca85f-3f83-4bcc-8c18-b671291bac31.jpg)

Updated Servers: Used the ansible command with the apt module and the update_cache option to update all of the remote servers in the inventory file. This command is equivalent to running the sudo apt update command on each of the servers.
![sudo apt-update, errors fixed](https://user-images.githubusercontent.com/91312467/234472424-69db7897-72b9-4114-8e22-e253ce88df1f.jpg)

Overall, this project provides a basic introduction to using Ansible for server automation. With this foundation, one can begin to learn more advanced Ansible concepts, such as writing Ansible playbooks to automate complex tasks, managing server configurations with Ansible roles, and integrating Ansible with other tools and services.

