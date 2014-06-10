# Ansible role : apticron

Installs and configure apticron on Debian/Ubuntu Linux servers.

## Role Variables

### Mandatory

`vars/main.yml`

| Name | Description |
| ---- | ----------- |
| apticron_email | Set email to a space separated list. |

### Defaults

`defaults/main.yml`

| Name |
| ---- |
| update_cache |
| cache_valid_time |
| apticron_file |
| apticron_group |
| apticron_owner |
| apticron_mode |
| apticron_frequency |


### More configuration

`vars/main.yml`

| Name |
| ---- |
| apticron_diff_only |
| apticron_listchanges_profile |
| apticron_all_fqdns |
| apticron_system |
| apticron_ipaddressnum |
| apticron_ipaddresses |
| apticron_notify_holds |
| apticron_notify_new |
| apticron_notify_no_updates |
| apticron_custom_subject |
| apticron_custom_no_updates_subject |
| apticron_custom_from |

## Requirements

None.

## Dependencies

None.

## License

MIT

## Author Information

[Simon Constans](http://www.sconstans.fr)
