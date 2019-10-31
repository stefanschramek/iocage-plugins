# iocage-plugins
## How to install a plugin
### Fetch plugin configuration
```
fetch https://raw.githubusercontent.com/stefanschramek/iocage-plugins/master/sonarr3.json
```
### Install plugin
```
iocage fetch --plugin-file -n sonarr3.json dhcp=on vnet=on bpf=yes
```
