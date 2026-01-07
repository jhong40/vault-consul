# vault-consul

### removal 
```
systemctl stop vault consul
systemctl disable vault consul

rm -fr /etc/systemd/system/vault.service
rm -fr /etc/systemd/system/consul.service
systemctl daemon-reload

which vault consul    # remove them
rm -fr /etc/vault.d
rm -fr /etc/consul.d

rm -fr /opt/consul
rm -fr /opt/vault

rm -fr /var/log/vault
rm -fr /var/log/consul

```
