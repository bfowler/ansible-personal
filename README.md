# README

Boostrap:

```
sudo apt update
sudo apt install -y git python3-pip python3-venv
git clone https://github.com/bfowler/ansible-personal.git
cd ansible-home

python3 -m venv venv
./venv/bin/pip install -r requirements.txt
./venv/bin/ansible-galaxy install -r requirements.yaml

```

To deploy homelab:

`./venv/bin/ansible-playbook -vvi inventory/personal playbooks/lab.yaml`

## Credit for these scripts goes to @paulbovbel (https://github.com/paulbovbel/ansible-home.git)

