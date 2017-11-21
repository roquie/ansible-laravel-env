# Ansible Laravel ENV

<br />

This role configure Laravel and install depends.

## Example playbook

[Here.](./tests)

## Install

```
ansible-galaxy install roquie.ansible-laravel-env
```

## Dependencies

* \>= Ansible 2.4
* \>= Vagrant 2.0 for testing runs.

## Supported OS

For now supports:
* Ubuntu 16.04 LTS
* Ubuntu 14.04 LTS

## Todo

* [ ] Change variables to normal name.
* [ ] Add `yarn` pkg manager for native & docker tasks.
* [ ] Complete tests.

## Vagrant

* `cd /path/to/project`
* `cd tests && ansible-galaxy install -r requirements.yml && cd ..`
* `vagrant up --provision` 

## License

MIT
