fzf
======

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-fzf.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-fzf)

Install [fzf](https://github.com/junegunn/fzf).

Notice
-------

* If this role succeeds, the result's changed attribute is always true.

Requirements
------------

* [motemen/ghq](https://github.com/motemen/ghq)

Role Variables
--------------

* ghq_executable: The executable path of ghq command. The default is "ghq".

Dependencies
------------

* [suzuki-shunsuke.ghq-module](https://galaxy.ansible.com/suzuki-shunsuke/ghq-module/)

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - suzuki-shunsuke.fzf
```

License
-------

MIT
