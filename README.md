# clockify

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/clockify)
[![General Workflow](https://github.com/rolehippie/clockify/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/clockify/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/clockify/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/clockify/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/clockify/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/clockify/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/clockify)](https://github.com/rolehippie/clockify/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.clockify-blue)](https://galaxy.ansible.com/rolehippie/clockify)

Ansible role to install clockify time tracking.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [clockify_package](#clockify_package)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### clockify_package

Download URL for the package to install

#### Default value

```YAML
clockify_package: https://clockify.me/downloads/Clockify_Setup.deb
```

## Discovered Tags

**_clockify_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
