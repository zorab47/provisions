Provisions
==========

A set of software tools automatically installed via Ansible.

Installation
------------

1. Change the username in `roles/dev/vars/main.yml` to your username
2. Install Ansible: `sudo apt-get install ansible`
3. Run the installation `ansible-playbook -i inventory --ask-sudo=pass dev.yml`

Tools
-----

- autojump
- blink(1)
- compton
- fish, friendly interactive shell
- fzf, cli fuzzy finder
- git
- i3, tiling window manager
- j4-dmenu-desktop
- jrnl
- neovim
- ranger, cli file manager
- rofi, app launcher
- shellcheck
- tmux
- vim
- xsel
- yubikey
