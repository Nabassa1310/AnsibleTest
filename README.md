# Introduction 
TODO: Give a short introduction of your project. Let this section explain the objectives or the motivation behind this project. 

# Ansible directory structure cheatsheet

````bash
├── ansible.cfg
├── inventories
│   ├── production
│   │   ├── hosts
│   └── staging
│       └── hosts
├── playbooks
│   └──  playbook-sample.yml
├── README.md
├── roles
│   └── role-sample
│       ├── defaults
│       │   └── main.yml
│       ├── handlers
│       │   └── main.yml
│       ├── meta
│       │   └── main.yml
│       ├── README.md
│       ├── tasks
│       │   ├── main.yml
│       │   └── task-sample.yml
│       ├── tests
│       │   ├── inventory
│       │   └── test.yml
│       └── vars
│           └── main.yml
└── templates
````
