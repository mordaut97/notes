```bash
apt-get remove cloud.init netplan.io udisks2 multipath-tools unattended-upgrades cloud-init lxde snapd
apt-get install NetworkManager
systemctl disable systemd-networkd
rm /usr/lib/NetworkManager/conf.d/10-globally-managed-devices.conf
```