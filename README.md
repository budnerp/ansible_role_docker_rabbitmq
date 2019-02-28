# Ansible role for RabbitMQ
Ansible role for RabbitMQ 3.7 for CentOS 7

## What's inside?
1. Interesting RabbitMQ dirs and files: 
    ```
    ...
    ```
2. Custom settings as per `defaults/main.yml`
   
## Tested on

## Installation
1. Navigate to Ansible's roles folder
2. Add the repo to git modules
    ```
    git submodule add https://github.com/budnerp/ansible_role_rabbitmq.git ansible_role_rabbitmq
    ```
3. Add the role to Ansible's playbook file
    ```    
    roles:
    [...]
        - ansible_role_rabbitmq
    [...]
    ```

## Other links
- RabbitMQ [http://www.rabbitmq.com/]()
- RabbitMQ Server on GitHub [https://github.com/rabbitmq/rabbitmq-server]()

## TO DO
-[ ] add dependencies 

## License
Copyright (c) We Are Interactive under the MIT license.