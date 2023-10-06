# Ansible playbook for developer's linux environment

This playbook is meant to work on fresh and minimal stable Debian OS.
It prepares machine for developers that work with tilling window managers (i3 here)
and neovim as their IDE.

## To run this playbook after Debian installation

1. Install sudo, git and ansible package as root user
2. Add your user to sudoers
3. Clone this repository
4. Run `ansible-playbook -u USER -i hosts -K playbook.yml --connection=local`
5. Reboot
6. Choose i3 in the right corner of login screen
