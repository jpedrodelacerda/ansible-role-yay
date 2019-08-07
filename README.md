# Yay
Simple Yay installation on ArchLinux

## Requirements
None.

## Role Variables
`colored_output:` Whether the pacman config should display colored output. Can be `true` or `false`.

## Dependencies:
None.

## Example Playbook
```
- hosts: server
  roles:
    - { role: jpedrodelacerda.yay }
```

## License
MIT/BSD
