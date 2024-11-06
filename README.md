## pip

[![CI](https://github.com/Oefenweb/ansible-pip/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-pip/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-pip-blue.svg)](https://galaxy.ansible.com/Oefenweb/pip)

Set up (the latest version of) [pip](https://pypi.python.org/pypi/pip) in Debian-like systems.

#### Requirements

* `python(2|3)` (will be installed)
* `python(2|3)-dev` (will be installed)
* `curl` (will be installed)

when using `pip_install_method: get-pip`

#### Variables

* `pip_install_method`: [default: `native`]: The way to install `pip` (e.g. `native` (from Ubuntu/Debian repo) or `get-pip`, `< 24.04` only)

* `pip_python_version_major` [default: `3`]: Python version to install `pip` for

* `pip_install`: [default: `[]`]: Additional packages to install

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.pip
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-pip/issues)!
