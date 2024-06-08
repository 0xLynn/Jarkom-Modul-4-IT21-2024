# VLSM - GNS3
![toplo](https://github.com/0xLynn/Jarkom-Modul-4-IT21-2024/assets/143694889/7e76bde5-fad2-41a9-a435-5448a6a7c50b)

## Tree
![VLSM  MConverter eu](https://github.com/0xLynn/Jarkom-Modul-4-IT21-2024/assets/143694889/3d0d11fa-fe72-4edf-b1b7-55bb3fb0ab40)

## Pembagian IP
![pembagi](https://github.com/0xLynn/Jarkom-Modul-4-IT21-2024/assets/143694889/9ad228e9-8a9e-4d6b-9e48-84559860fd14)

## Konfigurasi Network

### JAWA
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet dhcp

#A15
auto eth1
iface eth1 inet static
address 10.74.21.197 
netmask 255.255.255.252

#A7
auto eth2
iface eth2 inet static
address 10.74.21.181
netmask 255.255.255.252

#A6
auto eth3
iface eth3 inet static
address 10.74.21.177
netmask 255.255.255.252
```

### SUMATERA
```
auto lo
iface lo inet loopback

#A15
auto eth0
iface eth0 inet static
address 10.74.21.198
netmask 255.255.255.252
gateway 10.74.21.197 

#A16
auto eth1
iface eth1 inet static
address 10.74.21.201
netmask 255.255.255.252

#A18
auto eth2
iface eth2 inet static
address 10.74.21.65 
netmask 255.255.255.224
```

### KALIMANTAN
```
auto eth0
iface eth0 inet static
address 10.74.21.182
netmask 255.255.255.252
gateway 10.74.21.181

auto eth1
iface eth1 inet static
address 10.74.21.185
netmask 255.255.255.252
```

### SULAWESI
```
auto eth0
iface eth0 inet static
address 10.74.21.178
netmask 255.255.255.252

auto eth1
iface eth1 inet static
address 10.74.21.161  
netmask 255.255.255.248

auto eth1
iface eth1 inet static
address 10.74.20.129 
netmask 255.255.255.128
```

### SUMATERA-UTARA
```
auto eth0
iface eth0 inet static
address 10.74.21.66
netmask 255.255.255.224
gateway 10.74.21.65 

auto eth1
iface eth1 inet static
address 10.74.21.205 
netmask 255.255.255.252
```

### ACEH
```
auto eth0
iface eth0 inet static
address 10.76.21.206
netmask 255.255.255.252
gateway 10.76.21.205 

auto eth1
iface eth1 inet static
address 10.76.20.1 
netmask 255.255.255.128

auto eth1
iface eth1 inet static
address 10.76.21.129 
netmask 255.255.255.224
```

### LAMPUNG
```
auto eth0
iface eth0 inet static
address 10.74.21.202
netmask 255.255.255.252
gateway 10.74.21.201

auto eth1
iface eth1 inet static
address 10.74.19.1 
netmask 255.255.255.224
```

### Berawang-Tampu
```
auto eth0
iface eth0 inet static
address 10.74.20.2
netmask 255.255.255.128
gateway 10.74.20.1 
```

### Enang-Enang
```
auto eth0
iface eth0 inet static
address 10.74.20.3
netmask 255.255.255.128
gateway 10.74.20.1 
```

### Starland
```
auto eth0
iface eth0 inet static
address 10.74.20.4
netmask 255.255.255.128
gateway 10.74.20.1 

```

### Sabang
```
auto eth0
iface eth0 inet static
address 10.74.21.130
netmask 255.255.255.224
gateway 10.74.21.129 
```

### Lambaro
```
auto eth0
iface eth0 inet static
address 10.74.21.131
netmask 255.255.255.224
gateway 10.74.21.129 
```

### Sebuku
```
auto eth0
iface eth0 inet static
address 10.74.21.131
netmask 255.255.255.224
gateway 10.74.21.129 
```

### Sebesi
```
auto eth0
iface eth0 inet static
address 10.74.19.2
netmask 255.255.255.0
gateway 10.74.19.1 
```

### Samosir
```
auto eth0
iface eth0 inet static
address 10.74.21.67
netmask 255.255.255.224
gateway 10.74.21.65 
```

### Sibandang
```
auto eth0
iface eth0 inet static
address 10.74.21.68
netmask 255.255.255.224
gateway 10.74.21.65
```

### KALIMANTAN-UTARA
```
auto eth0
iface eth0 inet static
address 10.74.21.186
netmask 255.255.255.252
gateway 10.74.21.185

auto eth1
iface eth1 inet static
address 10.74.21.189
netmask 255.255.255.252
```

### KALIMANTAN-TIMUR
```
auto eth0
iface eth0 inet static
address 10.76.21.190
netmask 255.255.255.252
gateway 10.76.21.189

auto eth1
iface eth1 inet static
address 10.76.21.193
netmask 255.255.255.252

auto eth2
iface eth2 inet static
address 10.76.16.1
netmask 255.255.254.0
```

### KALIMANTAN-SELATAN
```
auto eth0
iface eth0 inet static
address 10.74.21.194
netmask 255.255.255.252
gateway 10.74.21.193

auto eth1
iface eth1 inet static
address 10.74.21.97 
netmask 255.255.255.224
```

### Batakan
```
auto eth0
iface eth0 inet static
address 10.76.0.4
netmask 255.255.248.0
gateway 10.76.0.1 
```

### Bajuing
```
auto eth0
iface eth0 inet static
address 10.74.0.2
netmask 255.255.248.0
gateway 10.74.0.1 

```

### Takisung
```
auto eth0
iface eth0 inet static
address 10.74.0.3
netmask 255.255.248.0
gateway 10.74.0.1 
```

### Angsana
```
auto eth0
iface eth0 inet static
address 10.76.21.98
netmask 255.255.255.224
gateway 10.76.21.97 
```

### Bangkirai
```
auto eth0
iface eth0 inet static
address 10.74.0.3
netmask 255.255.248.0
gateway 10.74.0.1 
```

### Lamaru
```
auto eth0
iface eth0 inet static
address 10.74.16.3
netmask 255.255.254.0
gateway 10.74.16.1
```

### Selimau
```
auto eth0
iface eth0 inet static
address 10.74.21.2
netmask 255.255.255.192
gateway 10.74.21.1 
```

### MAKASAR
```
auto eth0
iface eth0 inet static
address 10.74.21.2
netmask 255.255.255.192
gateway 10.74.21.1 
```

### BELAWA
```
auto eth0
iface eth0 inet static
address 10.74.21.2
netmask 255.255.255.192
gateway 10.74.21.1 
```

### MALUKU-UTARA
```
auto eth0
iface eth0 inet static
address 10.74.20.130
netmask 255.255.255.128
gateway 10.74.20.129 

auto eth1
iface eth1 inet static
address 10.74.8.1 
netmask 255.255.248.0
```

### Galesong
```
auto eth0
iface eth0 inet static
address 10.74.21.2
netmask 255.255.255.192
gateway 10.74.21.1 
```

### Topejawa-Takalar
```
auto eth0
iface eth0 inet static
address 10.74.21.2
netmask 255.255.255.192
gateway 10.74.21.1 
```

### Madini
```
auto eth0
iface eth0 inet static
address 10.74.21.2
netmask 255.255.255.192
gateway 10.74.21.1 
```

### Banu
```
auto eth0
iface eth0 inet static
address 10.76.21.3
netmask 255.255.255.192
gateway 10.76.21.1 
```

### Gorontalo
```
auto eth0
iface eth0 inet static
address 10.74.20.131
netmask 255.255.255.128
gateway 10.74.20.129 
```

### Marisa
```
auto eth0
iface eth0 inet static
address 10.74.20.132
netmask 255.255.255.128
gateway 10.74.20.129 
```

### Ternate
```
auto eth0
iface eth0 inet static
address 10.74.8.3
netmask 255.255.248.0
gateway 10.74.8.1 
```

### Morotai
```
auto eth0
iface eth0 inet static
address 10.74.8.2
netmask 255.255.248.0
gateway 10.74.8.1 
```

### Tobelo
```
auto eth0
iface eth0 inet static
address 10.74.8.4
netmask 255.255.248.0
gateway 10.74.8.1 
```

# CIDR - CPT
## Route
![image](https://github.com/0xLynn/Jarkom-Modul-4-IT21-2024/assets/117902615/e09c7e22-b058-4dcc-88d9-4a0f6ace496e)

## Penggabungan Subnet
### Subnet A
![image](https://github.com/0xLynn/Jarkom-Modul-4-IT21-2024/assets/117902615/a9992b05-2a42-4354-a4b0-dbee960f48dd)

### Subnet B
![image](https://github.com/0xLynn/Jarkom-Modul-4-IT21-2024/assets/117902615/bb7fa4f5-8fe6-4968-8ea6-9f00b48b0e25)

### Subnet C
![image](https://github.com/0xLynn/Jarkom-Modul-4-IT21-2024/assets/117902615/8b19a9a8-2c88-4829-9bac-3d032198538f)

### Subnet D
![image](https://github.com/0xLynn/Jarkom-Modul-4-IT21-2024/assets/117902615/a07662be-5b3a-46b0-b9aa-e6390593cbad)

### Subnet E
![image](https://github.com/0xLynn/Jarkom-Modul-4-IT21-2024/assets/117902615/7bc05aeb-ee09-4746-a3b1-6b56a0752a6f)

### Subnet F
![image](https://github.com/0xLynn/Jarkom-Modul-4-IT21-2024/assets/117902615/a0ee3822-cd59-4410-b91a-1cba750e00f9)

### Subnet G
![image](https://github.com/0xLynn/Jarkom-Modul-4-IT21-2024/assets/117902615/87baeb66-a93c-425d-b30a-cbb898229ee3)

### Subnet H
![image](https://github.com/0xLynn/Jarkom-Modul-4-IT21-2024/assets/117902615/0a635b70-4a10-493e-ac9d-aa167e33edfb)

## Tree
![image](https://github.com/0xLynn/Jarkom-Modul-4-IT21-2024/assets/117902615/35ac9b1e-f851-44bf-9471-b0a773e8dbaf)
