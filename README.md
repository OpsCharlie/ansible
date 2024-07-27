# ansible

ansible for installing my laptop

```sh
sudo apt install -y git python3-full python3-pip
mkdir -p ~/venv/3.12.3
python3 -m venv venv/3.12.3/
source ~/venv/3.12.3/bin/activate
pip install ansible

# install dropbox https://www.dropbox.com/install-linux
# Sync

git clone https://github.com/Charlietje/ansible.git

ansible-playbook -K local.yml
```
