# NanoPi-R2C-Plus-Experiments
NanoPi R2C Plus Experiments

01.How to update all software at once
```
opkg list-upgradable | cut -f 1 -d ' ' | while IFS='$\n' read -r line; do opkg install $line ; done
```
02. Install OpenVPN

```
opkg install openvpn-openssl
```

```
opkg install luci-app-openvpn
```
