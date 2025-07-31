### Cara Setting Route di windows
berfungsi untuk menghubungkan GNS3 VM dengan PC Real
```
route add 192.168.122.0 mask 255.255.255.0 192.168.56.103
```

### Cara menghapus semua aturan (rules) firewall
Masukkan code dibawah ini di Sheel di GNS3 VM, supaya PC real bisa mengakses GNS3 VM
```
sudo iptables -F
```
