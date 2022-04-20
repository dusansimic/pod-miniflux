# Miniflux Pod

> Ansible role for setting up Miniflux Pod that is managed by systemd.

## Variables

Required variables:

| Variable name | Description |
| ------------- | ----------- |
| app_tag | Miniflux image tag |
| publish_port | Port that is used on the host machine for the app service |

Required secrets:

| Secret name | Description |
| ----------- | ----------- |
| db_password | Postgres database password |
| app_admin_password | Admin password for Miniflux |

For additional variables, check the `miniflux` role.
