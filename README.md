# Ansible challenge

## Control machine configuration

Add access to the target machine

```Bash
ssh-copy-id username@server_ip
```

Install ansible

```Bash
sudo apt-add-repository ppa:ansible/ansible
sudo apt update
sudo apt install ansible
```

Add the machines hosts on **hosts** file.
