# Automate Network Provisioning on Private Cloud Network Architecture Using Ansible

Ansible as an agentless open source IT automation engine can help to orchestrate advanced workflows. This tool has been used in many different cases, whether in programming or networking. In this study case, there are:

* IOS Routers
* Virtual Switches
* CloudStack
* Ansible

That would be built as an environment, Ansible will act as a control node. The goal of this project is to complete network configuration L2, L3, and a little bit of VXLAN, on IOS Routers and Virtual Switches that will act as a managed node, using Ansible Playbook. This design topology idea has some reference from leaf and spine design, hope this can increase availability.



![Topology Project](https://github.com/user-attachments/assets/94ffaf35-74bd-47ea-a673-5ce56c67b8b3)

The objective is to connect headquarter and branch to CloudStack, without configuring each host on routers nor virtual switches back-to-back. 
