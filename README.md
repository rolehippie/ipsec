# ipsec

[![Build Status](https://cloud.drone.io/api/badges/rolehippie/ipsec/status.svg)](https://cloud.drone.io/rolehippie/ipsec)

Ansible role to configure ipsec

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
