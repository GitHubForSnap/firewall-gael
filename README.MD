# [firewall-gael](https://snapcraft.io/firewall-gael)

Firewall script launcher

**Configuration**

* IPv4 Configuration (optional)

```
   sudo vi /var/snap/firewall-gael/common/ipv4firewall.sh
   [...]
   chmod +x /var/snap/firewall-gael/common/ipv4firewall.sh
```

* IPv6 Configuration (optional)

```
   sudo vi /var/snap/firewall-gael/common/ipv6firewall.sh
   [...]
   chmod +x /var/snap/firewall-gael/common/ipv6firewall.sh
```

* Restart firewall-gael
`sudo snap restart firewall-gael.srv`

**2021-04-11**
* First release of firewall-gael on armhf, arm64, amd64

