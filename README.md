# Install kubernetes cluster on virutal machine

Make sure ssh less auth configured from ansible controller node

1. Change group_vars/env_variables file according to your environment
2. Change hosts file
3. Run 'ansible-playbook -i hosts setup_master_node.yml'
4. Run 'ansible-playbook -i hosts setup_worker_nodes.yml'

