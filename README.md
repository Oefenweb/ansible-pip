## pip

[![Build Status](https://travis-ci.org/Oefenweb/ansible-pip.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-pip) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-pip-blue.svg)](https://galaxy.ansible.com/list#/roles/4386)

Set up (the latest version of) [pip](https://pypi.python.org/pypi/pip) and [setuptools](https://pypi.python.org/pypi/setuptools) in Debian-like systems.

#### Requirements

* `python` (will be installed)
* `python-dev` (will be installed)

#### Variables

None

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - pip
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-pip/issues)!
