# Kubernetes-node-setup-with-Ansible-playbooks

Setting up Kubernetes cluster manually can be pain in the \*\*s, so thought of utlizing Ansible playbook to setup Kubernetes. 
You can use this Ansbile playbook that taskes less than 5 minutes to get up and running with k8s cluster.

**Requirement:** 

- OS: Ubuntu #Playbook should work on other distros but may require tweaks in the playbook like changing apt to yum, etc.
- Authetication setup between Ansible and target nodes.
- Updated inventory and groups in Ansible Hosts file.
- Python3 on all hosts.

![](https://github.com/ashishsecdev/Kubernetes-node-setup-with-Ansible-playbook/blob/main/Ansible2K8s.jpg?raw=true)
> Kubernetes deloyment using Ansible playbook.

**Note:** Published Ansible playbook is entirely based on my research and all these taks were tested at the time of publishing on Ubuntu 21.10. Also, few of these tasks might be similar to other published playbooks, so please DM to get it added in the references.

> I am still updating the playbook and will update the latest Master node setup steps.

**References:** 
To be added

**We can use this repo as one stop shop for all K8s related setup playbooks.**

**Pull Requests:**
- Please add your version playbook via raising PR.
- Limit pull requests to as few possible issues.
