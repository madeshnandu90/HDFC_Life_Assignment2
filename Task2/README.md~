## Ansible Playbook to perform patching on RHEl/CentOS Servers and Upgrade Apache from older to latest version.

## Pre-requiesties to use this ansible playbook is:
     1.Install ansible on master ansible server.This controls ansible clients.

     2.After created master server you have to enable passwordless authnitication between master server and client servers.

     3.Add client server details in /etc/ansible/hosts(i.e inventory file) file in master server.In this cause i created one group called dev-redhat.
            Example:cat hosts
                     [dev-redhat]
                       testserver1
                       testserver2

     4.Now write a playbook for your tasks.Playbooks are written in YAMl.

     5.In master server run bellow command to excute your play book.(For example you have written linuxpatching.yml)
      
                 ansible-playbook linuxpatching.yml

          Note:Before running the above command we need to stop apache/httpd.services application on clients.

                 ansible-playbook apacheupgrdage.yml
                     











