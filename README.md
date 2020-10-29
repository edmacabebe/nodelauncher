# Update Horizen Nodes to Latest

## Assumptions

  1. Python and Ansible is installed in your Jump or Bastion Box
  2. Can SSH to target Zen PoS Servers
  3. Configure the Inventory of Servers to update

      * Goto inventory/hosts and update the playbook: playbooks/zend-upgrade-playbook.yml the target server group

## Invocation Command

  ```
    ansible-playbook playbooks/zend-upgrade-playbook.yml
  ```