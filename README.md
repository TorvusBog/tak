# tak
Ansible playbook to install the TAK Server

It's designed to work under Rocky Linux and Debian-like Linux servers. The playbook should work until the certificates creation for the propper use of the server, dashboards and clientes.

Please replace the files with your desired release:

    .
    ├── inventory
    │   └── hosts
    ├── playbook.yml
    └── roles
        ├── certificates
        │   └── tasks
        │       └── main.yml
        ├── common
        │   └── tasks
        │       └── main.yml
        ├── java
        │   └── tasks
        │       └── main.yml
        ├── postgresql
        │   └── tasks
        │       └── main.yml
        ├── service
        │   └── tasks
        │       └── main.yml
        └── takserver
            ├── files
            │   ├── takserver-5.0-RELEASE69.noarch.rpm
            │   └── takserver_5.0-RELEASE69_all.deb
            └── tasks
                └── main.yml
