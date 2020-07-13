Requirements
pip install -U -I 'ansible[azure]'

Example command:
ansible-playbook playbook.yaml -e env_tag=dev -e record_name=test2 -e ip_address=10.0.0.4

