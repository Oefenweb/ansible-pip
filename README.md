## pip

[![CI](https://github.com/Oefenweb/ansible-pip/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-pip/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-pip-blue.svg)](https://galaxy.ansible.com/Oefenweb/pip)

Set up (the latest version of) [pip](https://pypi.python.org/pypi/pip), [wheel](https://packaging.python.org/key_projects/#wheel) and [setuptools](https://packaging.python.org/key_projects/#setuptools) in Debian-like systems.

#### Requirements

* `python(2|3)` (will be installed)
* `python(2|3)-dev` (will be installed)
* `curl` (will be installed)

#### Variables

* `pip_python_version_major` [default: `2`]: Python version to install `pip` for.
* `pip_python_version` [default: `pip_python_version`]: Deprecated

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
