# Ansible Collection - eengstrom.stow

<!-- [![Build Status](https://travis-ci.com/geerlingguy/ansible-collection-k8s.svg?branch=master)](https://travis-ci.com/geerlingguy/ansible-collection-k8s) -->

Ansible collection with roles to install and modules to use GNU `stow`.

## Usage

Install this collection locally:

    ansible-galaxy collection install eengstrom.stow -p ./collections

Then you can use the role from the collection in your playbooks:

    ---
    - hosts: all

      collections:
        - eengstrom.stow

      roles:
        - stow


## Documentation

[Full documentation for GNU `stow`](https://www.gnu.org/software/stow/manual/stow.html).

## Testing

TBD

## Acknowledgements

The `stow` module was originally written by (and imported directly from) Caian Rais Ertl's [ansible-stow](https://github.com/caian-org/ansible-stow).
