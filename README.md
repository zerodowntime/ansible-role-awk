# motd

Ansible role install AWK

## Installation

```yaml
   ansible-galaxy install zerodowntime.awk
```

## Requirements

This role requires Ansible 2.5 or higher.

Supported platforms:

```yaml
  platforms:
    - name: EL
      versions:
        - 7
```

## Default role variables

| Variable name      | Required? |  Type  | Description             |
|:------------------ |:---------:|:------:|:----------------------- |
| awk__package_state |    yes    | string | installed package state |
| awk__package_name  |    yes    | string | installed package name  | 

**All variables are described in [defaults/main.yml](defaults/main.yml) file.**

## Example Playbook

```yaml
  - hosts: all
    become: true
    roles:

    - role: zerodowntime.awk
```

## License

[Apache License 2.0](LICENSE)

## Support

ansible@zerodowntime.pl
