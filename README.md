# OTUS-LAB-9
 Автоматизация администрирования. Ansible. 

Решил сразу делать задание со звездочкой.

Структура каталога с ролью:
<pre>
.
├── ansible.cfg
├── provision
│   ├── playbook.yml
│   └── roles
│       └── otus_nginx
│           ├── defaults
│           │   └── main.yml
│           ├── files
│           ├── handlers
│           │   └── main.yml
│           ├── tasks
│           │   └── main.yml
│           ├── templates
│           │   └── nginx.conf.j2
│           └── vars
│               └── main.yml
└── Vagrantfile
</pre>
