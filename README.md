# ansible
ansible for installing my laptop

```
apt-add-repository ppa:ansible/ansible
apt update
apt install -y git ansible

git clone --recurse-submodules https://github.com/Charlietje/ansible.git

ansible-playbook -K local.yml
```
