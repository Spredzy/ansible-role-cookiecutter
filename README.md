# ansible-role-cookiecutter

A cookiecutter template for multi-distro support Ansible role

## Requierements

One needs to install `cookiecutter` first before being able to use this
project.

To install `cookiecutter` run:

```
pip install cookiecutter
```


## How does it work ?

Simply clone this repository, and run `cookiecutter` using this repository
as a template, it will then generate a ready to use ansible-role.

```
#> git clone https://github.com/Spredzy/ansible-role-cookiecutter
#> cookiecutter ansible-role-cookiecutter
full_name [John Doe]: Jane Doe
email [john@doe.com]: jane@doe.com
description [adescription]: An ansible role to install and configure rmilter
project_name [aproject]: rmilter
#> tree ansible-role-rmilter
ansible-role-rmilter
├── defaults
├── files
├── handlers
│   └── main.yml
├── meta
│   └── main.yml
├── README.md
├── tasks
│   ├── Debian.yml
│   ├── FreeBSD.yml
│   ├── main.yml
│   └── RedHat.yml
├── templates
└── vars
    ├── Debian.yml
    ├── FreeBSD.yml
    └── RedHat.yml

7 directories, 10 files
#>

```

## License

Apache 2.0


## Author

Yanis Guenane  <yanis+ansible@guenane.org>
