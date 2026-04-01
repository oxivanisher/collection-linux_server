## 2026-04-01 (2)
* Remove redundant become_user: root in all roles

## 2026-04-01
* openvpn_client: fix config file permissions to 0600, use systemd_service module
* mysql: fix backup script permissions to 0700
* ansible_userspace: use systemd_service module instead of generic service module

## 2026-03-27
* Bump for portainer to support custom CA to trust

## 2026-02-26
* Bump for portainer role to not fill the syslog

## 2026-02-20
* Bump for ufw role. Migrate ufw_mgmt_src_iprange to be a list.

## 2026-01-16
* Bump for ansible_userspace yaml syntax

## 2025-11-23
* Ansible 2.5 porting in all roles

## 2025-10-25
* Bump for ufw role supporting check mode
* Bump for openvpn role supporting check mode
* Bump for portainer role to use docker-compose plugin package for v2 and support check mode

## 2025-10.05
* Lookup user homes instead of guesstimating
* Install trixie ansible dep for pip

## 2025-10-04
* Ensure switch variable is bool

## 2025-09-30
* Bump for jump user role idempotency improvement

## 2025-08-21
* Bump for ansible_userspace role (adding ansible-navigator)

## 2025-03-13
* Bump for portainer role, adding Portainer SSL Port

## 2025-03-01
* Bump for openvpn_client removing compression. This will break your connections!

## 2025-02-08
* Bump for all roles to remove unused tests directory to make linter happy
* Everything is now correctly linted

## 2024-11-13
* Bump for ansible userspace for tab autocomplete

## 2024-09-10
* Bump for portainer role supporting docker compose v2

## 2024-06-28
* Adding supported minimal version for linter
* Improve readme

## 2024-05-01
* UFW role: Add Readme and rework only open SSH for ansible port from management and not public

## 2024-04-29
* Portainer role: now has a docker prune service
