# Ansible Docker for Ubuntu 18.04

Ubuntu Server 18.04に対してDocker EngineをインストールするためのAnsible Playbookです。

## 使い方

```bash
sudo apt update && sudo apt install -y ansible python
git clone https://github.com/dozonot/ansible-docker-for-ubuntu1804.git
cd ansible-docker-for-ubuntu1804
ansible-playbook -i localhost, -c local playbook.yml
sudo reboot
```
