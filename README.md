### Ansible for Network Engineers

#### Environment Configuration

- Create a virtual environment `python3 -m venv venv`
- Activate environment`source venv/bin/activate` and upgrade pip `python3 -m pip install --upgrade pip`
- Individual packages installation `python3 -m pip install ansible`
- Install project packages`python3 -m pip install -r requirements.txt`
- Stop running environment`deactivate`
- Ansible config `ansible-config init --disabled > ansible.cfg` OR with plugins `ansible-config init --disabled -t all > ansible.cfg`
- Checking Ansible configuration file`ansible-playbook 01_config/check_ansible_config.yml`