## Samba role

Some description for Samba role would be nice. Any volunteers?

### Parameters

**samba_shares** (type `array`, default `[]`)

Example:
```yaml
samba_shares:
 - name: share_name
   path: /path/to/share
```

**samba_users** (type `array`, default `[]`)

Example:
```yaml
samba_users:
 - username: vagrant
   password: vagrant
```