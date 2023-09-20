
# Reverse Tcp Tunnel Installer For Debian and Ubuntu

Reverse Tcp Tunnel with custom sni handshake

## OS Supported:


```bash
  Ubuntu 22.04
  Ubuntu 20.04
  Debian 12
  Debian 11
```





## Install

Clone the project

```bash
  bash -c "$(curl -L https://raw.githubusercontent.com/azadrahorg/RTT-Tunnel-Helper/main/RTT-Tunnel-Helper.sh)"
```

### How to Manage
Stop the service.
```bash
  systemctl stop tunnel.service
```
View the status of the service.
```bash
  systemctl status tunnel.service
```
Restart the service.
```bash
systemctl restart tunnel.service
```


## Related

Thanks to

https://github.com/radkesvat/ReverseTlsTunnel/tree/master

