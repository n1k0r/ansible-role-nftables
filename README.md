# nftables role for Ansible

## Variables

```yaml
nftables_config: nftables.conf.j2 # optional
```

If `nftables_config` is not specified then [default](templates/default_nftables.conf.j2) is used.
