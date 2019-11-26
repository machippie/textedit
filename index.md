
## Default Variables

### textedit_read_encoding

Read text encoding

#### Default value

```yaml
textedit_read_encoding: 4
```

### textedit_richtext

Enable rich text editing mode

#### Default value

```yaml
textedit_richtext: 0
```

### textedit_user

User to run user-specific commands

#### Default value

```yaml
textedit_user | default(homebrew_user) | default(ansible_user_id)
```

### textedit_write_encoding

Write text encoding

#### Default value

```yaml
textedit_write_encoding: 4
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
