# Helm

## Install/Upgrade chart/release

```shell
$ helm upgrade --install \
    -f Chart.yaml \
    --values=dev-values.yaml \
    release-name /path/to/release-name/
```

## Debugging

### Get deployed manifest

```shell
$ helm get manifest release-name
```