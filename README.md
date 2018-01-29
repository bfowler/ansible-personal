# README

Boostrap:

```
sudo apt update
sudo apt install -y git python-pip
sudo -H pip install pip --upgrade
sudo -H pip install ansible
git clone https://github.com/paulbovbel/ansible-home.git
cd ansible-home
```

To deploy on the current machine:

`ansible-playbook -Kvvi inventory/personal playbooks/developer.yaml`

To deploy homelab:

`ansible-playbook -Kvvi inventory/homelab playbooks/homelab.yaml`

To encrypt all vault files:

`ansible-vault encrypt $(find . -path *vault/*)`


TODO outstanding components:
  - xenserver + VMs setup
  - nas4free VM
  - pfsense VM
