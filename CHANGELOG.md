# Changelog

All notable changes to this project will be documented in this file.

- [1.2.0 (2022-12-18)](#120-2022-12-18)
- [1.1.0 (2022-01-28)](#110-2022-01-28)
- [1.0.0 (2021-10-11)](#100-2021-10-11)

---

<a name="1.2.0"></a>
## [1.2.0](https://github.com/aisbergg/ansible-role-cron/compare/v1.1.0...v1.2.0) (2022-12-18)

### Bug Fixes

- rename option 'file' to 'cron_file' to match the module definition

### CI Configuration

- add branch explicitly to make Ansible import action happy
- bump Ansible Galaxy action version

### Chores

- update linting config and add tox.ini
- don't use bump2version to include the CHANGELOG in the bump commit, it doesn't do a good job


<a name="1.1.0"></a>
## [1.1.0](https://github.com/aisbergg/ansible-role-cron/compare/v1.0.0...v1.1.0) (2022-01-28)

### CI Configuration

- fix automatic release and publish process

### Chores

- include changelog in bump commits
- update changelog template
- **requirements.yml:** add role requirements


<a name="1.0.0"></a>
## [1.0.0]() (2021-10-11)

Initial Release
