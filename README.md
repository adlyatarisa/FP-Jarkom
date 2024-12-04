# Laporan Final Project Jarkom

| Nama | NRP |
| ---- | :-: |
| Chelsea Vania | 5027231006 |
| Fiorenza Adelia Nalle | 5027231053 |
| Adlya Isriena Aftarisya | 5027231066 |
| Harwinda | 5027231079 |

## Topologi dan subnetting
![topologi](images/image.png)

## Pembagian IP
![alt text](images/image2.png)

## Konfigurasi dan Routing
### Router ARA Tech
Interfaces
```
# A1
ip address 10.66.0.1 255.255.255.252

# A3
ip address 10.66.0.132 255.255.255.252

# A5
ip address 10.66.2.1 255.255.255.252

# A7
ip address 10.66.2.69 255.255.255.252

# A9
ip address 10.66.2.135 255.255.255.252
```
Static Route
### Lt 1
Interfaces
```
# A1
ip address 10.66.0.2 255.255.255.252

# A2
ip address 10.66.0.5 255.255.255.128
```
Static Route
```
routing taro sini
```

### Ruang server dan Datacenter
```
ip address 10.66.0.6 255.255.255.128
```

### Departemen IT
```
ip address 10.66.0.7 255.255.255.128
```

### Departemen HR
```
ip address 10.66.0.8 255.255.255.128
```

### Lt 2
Interfaces
```
# A3
ip address 10.66.0.134 255.255.255.252

# A4
ip address 10.66.0.137 255.255.255.128
```
Static Route
```
taro sini
```
### Departemen R&D
```
ip address 10.66.0.138 255.255.255.128
```

### Departemen Pemasaran
```
ip address 10.66.0.139 255.255.255.128
```

### Departemen Penjualan
```
ip address 10.66.0.140 255.255.255.128
```

### Lt 3
Interfaces
```
# A5
ip address 10.66.2.2 255.255.255.252

# A6
ip address 10.66.2.5 255.255.255.192
```
Static Route
```
taro sini
```

### Departemen Keuangan
```
ip address 10.66.2.6 255.255.255.192
```

### Departemen Legal
```
ip address 10.66.2.7 255.255.255.192
```

### Lt 4
Interfaces
```
# A7
ip address 10.66.2.70 255.255.255.252

# A8
ip address 10.66.2.73 255.255.255.192
```
Static Route
```
taro sini
```

### Departemen Manajemen
```
ip address 10.66.2.74 255.255.255.192
```

### Departemen Customer Support
```
ip addrress 10.66.2.75 255.255.255.192
```

### Lt 5
Interfaces
```
# A9
ip address 10.66.2.138 255.255.255.252

# A10
ip address 10.66.2.141 255.255.255.192
```
Static Route
```
taro sini
```
### Departemen Cybersecurity
```
ip address 10.66.2.142 255.255.255.192
```

### Departemen HR
```
ip address 10.66.2.143 255.255.255.192
```

### Ruang Meeting
```
ip address 10.66.2.144 255.255.255.192
```