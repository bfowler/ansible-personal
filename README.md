# README

## Boostrap:

```
sudo apt update
sudo apt install -y git python3-pip python3-venv
git clone https://github.com/bfowler/ansible-personal.git
cd ansible-personal

python3 -m venv venv
./venv/bin/pip install -r requirements.txt
```

## To deploy homelab:

`./venv/bin/ansible-playbook -vvi inventory/hosts playbooks/lab.yaml`

#### Credit for these scripts goes to @paulbovbel (https://github.com/paulbovbel/ansible-home.git)

