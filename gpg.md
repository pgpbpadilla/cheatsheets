# GPG

## Restart GPG agent

```shell
$ gpgconf --kill gpg-agent
```

## Export secret keys

```shell
$ gpg --armor \
  --export-secret-key user.email@domain.com > \
  /path/to/private.gpg
```
