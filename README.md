# work

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/ipsec) [![Testing Build](https://github.com/rolehippie/ipsec/workflows/testing/badge.svg)](https://github.com/rolehippie/ipsec/actions?query=workflow%3Atesting) [![Readme Build](https://github.com/rolehippie/ipsec/workflows/readme/badge.svg)](https://github.com/rolehippie/ipsec/actions?query=workflow%3Areadme) [![Galaxy Build](https://github.com/rolehippie/ipsec/workflows/galaxy/badge.svg)](https://github.com/rolehippie/ipsec/actions?query=workflow%3Agalaxy) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/ipsec)](https://github.com/rolehippie/ipsec/blob/master/LICENSE) 

Ansible role to configure IPsec tunnels. 

## Sponsor 

[![Proact Deutschland GmbH](https://proact.eu/wp-content/uploads/2020/03/proact-logo.png)](https://proact.eu) 

Building and improving this Ansible role have been sponsored by my employer **Proact Deutschland GmbH**.

## Table of content

* [Default Variables](#default-variables)
  * [ipsec_charon_debug](#ipsec_charon_debug)
  * [ipsec_sites_extra](#ipsec_sites_extra)
  * [ipsec_sites_general](#ipsec_sites_general)
  * [ipsec_unique_ids](#ipsec_unique_ids)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

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

## Dependencies

* None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
