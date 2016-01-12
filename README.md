# Ansible to Create Jenkins Machine

You'll need to have ansible already installed. And you need to have an ubuntu machine that you have ssh access.

###Changing Hosts File

>You find this line and put your ip address there. Even if it's your machine.
>
>[production]
>
>IP_ADDRESS


###Run the command:

> ansible-playbook production.yml -i hosts -l production
