# Intro
https://www.ansible.com/overview/it-automation

# Install ansible on Fedora
```shell
sudo dnf -y update
sudo dnf -y install ansible
```

Check if it's correctly installed by checking the version
```shell
ansible --version
```
# Run th example
To run this example, you have to checkout first a project
```shell
cd this_project_path
ansible-playbook -i hosts ./roles/test_common.yml
```
