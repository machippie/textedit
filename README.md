# textedit

[![Build Status](https://cloud.drone.io/api/badges/machippie/textedit/status.svg)](https://cloud.drone.io/machippie/textedit)

Ansible role to configure textedit

## Table of content

* [Default Variables](#default-variables)
  * [textedit_read_encoding](#textedit_read_encoding)
  * [textedit_richtext](#textedit_richtext)
  * [textedit_user](#textedit_user)
  * [textedit_write_encoding](#textedit_write_encoding)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

---

## Default Variables

### textedit_read_encoding

Read text encoding

#### Default value

```YAML
textedit_read_encoding: 4
```

### textedit_richtext

Enable rich text editing mode

#### Default value

```YAML
textedit_richtext: 0
```

### textedit_user

User to run user-specific commands, defaults to homebrew_user

### textedit_write_encoding

Write text encoding

#### Default value

```YAML
textedit_write_encoding: 4
```

## Dependencies

None.

## License

Apache-2.0

## Author

Thomas Boerger
