# ansible-fzf

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-fzf.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-fzf)

ansible role to install [fzf](https://github.com/junegunn/fzf).

## This role is deprecated and removed from Ansible Galaxy! (2019-02-12)

This role is deprecated because it isn't maintained for a long time.
I have removed this role from Ansible Galaxy.
Please use other role.

https://github.com/suzuki-shunsuke/ansible-fzf/issues/2

## Note

* If this role succeeds, the result's changed attribute is always true.

## Requirements

* [motemen/ghq](https://github.com/motemen/ghq)

## Role Variables

* ghq_executable: The executable path of ghq command. The default is "ghq".

## Dependencies

* [suzuki-shunsuke.ghq-module](https://galaxy.ansible.com/suzuki-shunsuke/ghq-module/)

## Example Playbook

```yaml
- hosts: servers
  roles:
    - suzuki-shunsuke.fzf
```

## License

[MIT](LICENSE)
