# Pulling at Threads

I started learning Ansible a long time ago, and it's been good fun. I realised early on how useful it could be for keeping the configuration of my computers in sync, but after a cursory glance at ansible-pull, I decided I should get some fundamentals down before digging deeper.

This repository presents a playing ground of sorts, where I can experiment with different approaches, and maybe also track what I've learned.

## Goals

I'd quite like to be able to use Ansible to take a new machine from a base install to a fully configured, self-updating system. A lot of this is already achieved by keeping my dotfiles under version control, but there are a few things (system-wide config files or the pacman hooks I use to update my master list packages) that I think Ansible would be better suited to.

## Things to figure out

- How to reuse roles between push and pull playbooks
- How to handle centralising SSH configuration
