[![Build Status](https://travis-ci.org/tvieira/ansible-powerline-fonts.svg?branch=master)](https://travis-ci.org/tvieira/ansible-powerline-fonts)
[![Ansible Galaxy](https://img.shields.io/ansible/role/20964.svg)](https://galaxy.ansible.com/tvieira//)

Powerline-Fonts
===============

This role installs the powerline fonts from the project [https://github.com/powerline/fonts](https://github.com/powerline/fonts).


Role Variables
--------------

No role variables need to set due to reasonable defaults.

```yaml
all_users:              # this role can configure for one or more users
  - user: foo           # username. Defaults to current user

all_fonts:              # the fonts you want to install. Defaults shown here.
  - RobotoMono          # the name of these fonts must match the name of the
  - SourceCodePro       # font directory
  - DejaVuSansMono
  - UbuntuMono
```

License
-------

GPLv3

Author Information
------------------

Tiago M. Vieira - [https://github.com/tvieira](https://github.com/tvieira)
Cruse, Si - [https://github.com/sicruse](https://github.com/sicruse)
Mark Stosberg - [https://github.com/markstos](https://github.com/markstos)
