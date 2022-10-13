```bash
apt-get install network-manager
systemctl disable systemd-networkd
rm /usr/lib/NetworkManager/conf.d/10-globally-managed-devices.conf
systemctl enable NetworkManager
apt-get remove cloud.init netplan.io udisks2 multipath-tools unattended-upgrades cloud-init lx. snapd
```ip 