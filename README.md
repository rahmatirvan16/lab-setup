### Cara Setting Route di windows
```
route add 192.168.122.0 mask 255.255.255.0 192.168.56.103
```

### Cara menghapus semua aturan (rules) firewall
Masukkan code dibawah ini di Sheel di GNS3 VM
```
sudo iptables -F
```
