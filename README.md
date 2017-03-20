# ansible_dcos_playbook
detailed playbook for setting up DC/OS 

this playbook does the following:
- fully updates centos 7
- latest docker yum repositories
- templated overrides for docker systemd  
- etcd installed on master nodes
- calico network overlay
- templatized configurations for docker networks for back and frontend using calico engine
- SSL certificates installed DCOS adminrouter / UI  ( see my letsencrypt repo: meetri/dehydrated-dcos )
- SSL certificates installed for docker api
- mounts an aws snapshot volume to designated nodes
- mounts an aws efs partition to designated nodes
