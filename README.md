# RedOS
Ansible scripts for configure RedOS

Exaple command line for running script
**ansible-playbook -i 192.168.111.101, --ask-become-pass --extra-vars variable_host=all RedOSLocalRepoServer.yml -u admin -k**

**dist_redos_make_local_repo_server.yml** - make yum local server repository for RedOS (CentOS 8), based on Apache (httpd) 
**conf_redos_config_work_station.yml** - make default configuration typical workstation
