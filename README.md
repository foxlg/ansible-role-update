# Ansible role 'update'

An Ansible role for updating systems to the latest packages.

## Requirements
Compatible and tested with:
- Arch Linux
- CentOS 7
- Fedora 25
- Linux Mint 18
- Ubuntu 16.10 or later

## Role Variables
| Variable                       | Default                          | Comments (type)  |
| :---                           | :---                             | :---             |
| as_user | foo | Declares the user as which {{ aur_app }} is run |
| aur_app | yaourt | (yaourt/pacaur) |

## Dependencies
No role dependencies

## Example Playbook
```Yaml
- hosts: foo
  roles:
    - { role: update, as_user: moocow, aur_app: yaourt }
```

## Testing

## License

BSD

## Contributors

Issues, feature requests, ideas, suggestions, etc. are appreciated and can be posted in the Issues section. Pull requests are also very welcome. Please create a topic branch for your proposed changes, it's the easiest way to merge back into the project.

- [Oscar Petersson](https://github.com/oscpe262/) (Maintainer)
