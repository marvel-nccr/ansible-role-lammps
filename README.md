[![Build Status](https://travis-ci.org/marvel-nccr/ansible-role-lammps.svg?branch=master)](https://travis-ci.org/marvel-nccr/ansible-role-lammps)

# Ansible Role: marvel-nccr.lammps

An ansible role that installs [LAMMPS](http://lammps.sandia.gov/) on Ubuntu.

## Installation

`ansible-galaxy install marvel-nccr.lammps`

## Role Variables

See `defaults/main.yml`

## Example Playbook

```yaml
  - hosts: servers
    roles:
    - role: marvel-nccr.lammps
```

## License

MIT

## Contact

Please direct inquiries regarding Quantum Mobile and associated ansible roles to the [AiiDA mailinglist](http://www.aiida.net/mailing-list/).
