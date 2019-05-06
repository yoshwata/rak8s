
# Template of setting files

`/inventory`
```toml
[dev]
pi001   ansible_host=<REPLACE_ME>
pi002   ansible_host=<REPLACE_ME>
pi003   ansible_host=<REPLACE_ME>

[master]
pi001
```

`group_vars/all.yml`
```
k3s_version: "<REPLACE_ME>"

https_master: "https://<REPLACE_ME>:6443"

k3s_token: "<REPLACE_ME>"
```
