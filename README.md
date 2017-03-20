# ansible_dcos_playbook
detailed playbook for setting up DC/OS 

this playbook does the following:
 -- fully updated centos 7 os
 -- latest docker yum repositories
 -- templated overrides for docker systemd  
 -- etcd installed on master nodes
 -- calico network overlay
 -- templatized configurations for docker networks for back and frontend using calico engine
 -- SSL certificates installed DCOS adminrouter / UI  ( see my letsencrypt repo )
 -- SSL certificates installed for docker api
 -- mounts a snapshot volume to designated nodes
 -- mounts a shared nfs partition to designated nodes
