# ipsec

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&amp;logoColor=white)](https://github.com/rolehippie/ipsec)
[![General Workflow](https://github.com/rolehippie/ipsec/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/ipsec/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/ipsec/actions/workflows/readme.yml/badge.svg)](https://github.com/rolehippie/ipsec/actions/workflows/readme.yml)
[![Galaxy Workflow](https://github.com/rolehippie/ipsec/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/ipsec/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/ipsec)](https://github.com/rolehippie/ipsec/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.ipsec-blue)](https://galaxy.ansible.com/rolehippie/ipsec)

Ansible role to configure IPsec tunnels.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Default Variables](#default-variables)
  - [ipsec_charon_debug](#ipsec_charon_debug)
  - [ipsec_sites_extra](#ipsec_sites_extra)
  - [ipsec_sites_general](#ipsec_sites_general)
  - [ipsec_unique_ids](#ipsec_unique_ids)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### ipsec_charon_debug

Debugging levels for charon

#### Default value

```YAML
ipsec_charon_debug: ike 1, knl 1, cfg 0
```

### ipsec_sites_extra

List of extra sites

#### Default value

```YAML
ipsec_sites_extra: []
```

### ipsec_sites_general

List of general sites

#### Default value

```YAML
ipsec_sites_general: []
```

### ipsec_unique_ids

Allow or disallow multiple ids

#### Default value

```YAML
ipsec_unique_ids: false
```

## Discovered Tags

**_ipsec_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
