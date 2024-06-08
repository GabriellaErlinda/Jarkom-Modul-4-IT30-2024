# Lapres-Jarkom-Modul-4-IT30-2024

## Anggota

| Nama                            | NRP          |
| ------------------------------- | ------------ |
| Gabriella Erlinda Wijaya        | `5027221018` |
| Aras Rizky Ananta               | `5027221053` |

## TOPOLOGI
### TOPOLOGI CPT-VLSM
![Topologi_CPT_IT30](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/401e7138-ec69-4689-bdf5-7cbe1f1f8d8e)

### TOPOLOGI GNS-CIDR


## RUTE
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/4912d299-18ab-4074-8549-ba491fc574dd)

## CPT-VLSM
### Tree -VLSM
Subnet besar yang dibentuk memiliki network ID 192.248.0.0 dengan netmask /19, sehingga didapatkan pembagian IP sebagai berikut
![VLSM_Tree_IT30](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/abfcc842-1d6f-4128-bc7d-4615cfc58a89)

### Pembagian IP -VLSM
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/02c603cc-1c6d-48b5-89c0-8e3c0893f9f3)

### Pembagian IP per node -VLSM
| SUBNET  | NODE               | IP              | SUBNET MASK     |
| ------- | ------------------ | --------------- | --------------- |
| `A1`    | JAWA               | 192.248.21.177  | 255.255.255.252 |
|         | SUMATERA           | 192.248.21.178  | 255.255.255.252 |
| `A2`    | SUMATERA           | 192.248.21.65   | 255.255.255.224 |
|         | SUMATERA-UTARA     | 192.248.21.66   | 255.255.255.224 |
|         | SAMOSIR            | 192.248.21.67   | 255.255.255.224 |
|         | SIBANDANG          | 192.248.21.68   | 255.255.255.224 |
| `A3`    | SUMATERA-UTARA     | 192.248.21.181  | 255.255.255.252 |
|         | ACEH               | 192.248.21.182  | 255.255.255.252 |
| `A4`    | ACEH               | 192.248.20.1    | 255.255.255.128 |
|         | BERAWANG-TAMPU     | 192.248.20.2    | 255.255.255.128 |
|         | ENANG-ENANG        | 192.248.20.3    | 255.255.255.128 |
|         | STARLAND           | 192.248.20.4    | 255.255.255.128 |
| `A5`    | ACEH               | 192.248.21.129  | 255.255.255.224 |
|         | SABANG             | 192.248.21.130  | 255.255.255.224 |
|         | LAMBARO            | 192.248.21.131  | 255.255.255.224 |
| `A6`    | SUMATERA           | 192.248.21.185  | 255.255.255.252 |
|         | LAMPUNG            | 192.248.21.186  | 255.255.255.252 |
| `A7`    | LAMPUNG            | 192.248.19.1    | 255.255.255.0   |
|         | SEBESI             | 192.248.19.2    | 255.255.255.0   |
|         | SEBUKU             | 192.248.19.3    | 255.255.255.0   |
| `A8`    | JAWA               | 192.248.21.189  | 255.255.255.252 |
|         | KALIMANTAN         | 192.248.21.190  | 255.255.255.252 |
| `A9`    | KALIMANTAN         | 192.248.21.193  | 255.255.255.252 |
|         | KALIMANTAN-UTARA   | 192.248.21.194  | 255.255.255.252 |
| `A10`   | KALIMANTAN-UTARA   | 192.248.18.1    | 255.255.255.0   |
|         | SELIMAU            | 192.248.18.2    | 255.255.255.0   |
| `A11`   | KALIMANTAN-UTARA   | 192.248.21.197  | 255.255.255.252 |
|         | KALIMANTAN-TIMUR   | 192.248.21.198  | 255.255.255.252 |
| `A12`   | KALIMANTAN-TIMUR   | 192.248.16.1    | 255.255.254.0   |
|         | BANGKIRAI          | 192.248.16.2    | 255.255.254.0   |
|         | LAMARU             | 192.248.16.3    | 255.255.254.0   |
| `A13`   | KALIMANTAN-TIMUR   | 192.248.21.201  | 255.255.255.252 |
|         | KALIMANTAN-SELATAN | 192.248.21.202  | 255.255.255.252 |
| `A14`   | KALIMANTAN-SELATAN | 192.248.21.97   | 255.255.255.224 |
|         | ANGSANA            | 192.248.21.98   | 255.255.255.224 |
| `A15`   | KALIMANTAN-SELATAN | 192.248.0.1     | 255.255.248.0   |
|         | BAJUIN             | 192.248.0.2     | 255.255.248.0   |
|         | TAKISUNG           | 192.248.0.3     | 255.255.248.0   |
|         | BATAKAN            | 192.248.0.4     | 255.255.248.0   |
| `A16`   | JAWA               | 192.248.21.205  | 255.255.255.252 |
|         | SULAWESI           | 192.248.21.206  | 255.255.255.252 |
| `A17`   | SULAWESI           | 192.248.20.129  | 255.255.255.128 |
|         | MALUKU-UTARA       | 192.248.20.130  | 255.255.255.128 |
|         | GORONTALO          | 192.248.20.131  | 255.255.255.128 |
|         | MARISA             | 192.248.20.132  | 255.255.255.128 |
| `A18`   | MALUKU-UTARA       | 192.248.8.1     | 255.255.248.0   |
|         | MOROTAI            | 192.248.8.2     | 255.255.248.0   |
|         | TOBELO             | 192.248.8.3     | 255.255.248.0   |
|         | TERNATE            | 192.248.8.4     | 255.255.248.0   |
| `A19`   | SULAWESI           | 192.248.21.161  | 255.255.255.248 |
|         | BELAWA             | 192.248.21.162  | 255.255.255.248 |
|         | MAKASAR            | 192.248.21.163  | 255.255.255.248 |
| `A20`   | MAKASAR            | 192.248.21.169  | 255.255.255.248 |
|         | GALESONG           | 192.248.21.170  | 255.255.255.248 |
|         | TOPEJAWA-TAKALAR   | 192.248.21.171  | 255.255.255.248 |
| `A21`   | BELAWA             | 192.248.21.1    | 255.255.255.192 |
|         | MADINI             | 192.248.21.2    | 255.255.255.192 |
|         | BARU               | 192.248.21.3    | 255.255.255.192 |

### Subnetting
Di sini kami mengambil contoh router Aceh dan client Lambaro dan Sabang, langkah-langkah ini dilakukan ke semua node yang ada
#### ACEH
Assignment IP subnet dilakukan dengan menjalankan command berikut pada terminal config:
```
interface <Nama interface>
ip address <IP address> <Netmask>
no shutdown
```
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/fabb685e-4bd4-44e5-a257-05df93c1aca1)
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/2bb05b45-a523-4021-b054-71fe6bda5f12)
Pada gambar di atas terlihat interface yang digunakan fa0/0 dengan IP `192.248.21.182` yang merupakan IP dari Aceh menuju subnet A3, interface fa0/1 dengan IP `192.248.21.129` yang merupakan IP dari Aceh menuju subnet A5, lalu interface fa1/0 dengan IP `192.248.20.1` yang merupakan IP dari Aceh menuju subnet A4

#### LAMBARO
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/dffe341b-9ec0-4706-918c-d0959225386e)

#### SABANG
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/8b82cbad-0286-47f7-af59-d28d26c10e58)


### Routing
#### JAWA
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/414cd8d3-3e36-44cc-a8f1-f109a46131cd)
Jawa yang terkoneksi langsung ke NAT akan menjadi router yang mensortir dan meneruskan request yang masuk ke pulau yang dituju (Sumatera, Kalimantan, atau Sulawesi) 

#### SUMATERA
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/90b0870a-a4b0-4a68-a7d7-53e1280a45ca)
Sumatera sebagai router yang terkoneksi langsung ke Jawa akan mengarahkannya ke subnet yang terkoneksi pada Sumatera (A2, A3, A4, A5, A6, A7)
- Routing subnet `192.248.21.180` (A3), `192.248.20.0` (A4), `192.248.21.187` (A5) dengan next hop ke Sumatera Utara (sesuai rute dari Jawa) 
- Routing subnet `192.248.19.0` (A7) dengan next hop ke Lampung
- Routing subnet `0.0.0.0` (A2) dengan next hop ke Jawa

#### SUMATERA-UTARA
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/6a57b5f5-e6d6-49ca-a9e0-b5b69e9f4cb8)
Sumatera Utara yang terkoneksi ke Sumatera akan menjadi 'jalan' untuk routing subnet A4 dan A5
- Routing subnet `192.248.20.0` (A4) dan `192.248.21.187` (A5) dengan next hop ke Aceh

#### ACEH
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/4c377fbe-2912-4066-920b-b95212efe392)
Aceh yang terhubung ke Sumatera Utara akan 'meminta' pembagian IP
- `0.0.0.0` berarti mengambil semua pesan dan diarahkan ke next hop Sumatera Utara

#### LAMPUNG
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/a5284a76-161c-461c-b4b3-8b8809da5fef)
Lampung yang terhubung ke Sumatera akan 'meminta' pembagian IP
- `0.0.0.0` berarti mengambil semua pesan dan diarahkan ke next hop Sumatera 

#### KALIMANTAN
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/3f572b55-366a-4a46-a737-ede1d0aab69d)
Kalimantan sebagai router yang terkoneksi langsung ke Jawa akan mengarahkannya ke subnet yang terkoneksi pada Kalimantan (A8, A9, A10, A11, A12, A13, A14, A15)
- Routing subnet `192.248.18.0` (A10), `192.248.21.196` (A11), `192.248.16.0` (A12), `192.248.21.200` (A13), `192.248.21.96` (A14), `192.248.0.0` (A15) dengan next hop ke Kalimantan Utara (sesuai rute dari Jawa) 
- Routing subnet `0.0.0.0` dengan next hop ke Jawa

#### KALIMANTAN-UTARA
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/d06a7b44-387f-4e3b-8512-4259cba6b782)
Kalimantan Utara yang terkoneksi ke Kalimantan akan 'meminta' IP dari Kalimantan
- Routing subnet `192.248.16.0` (A12), `192.248.21.200` (A13), `192.248.21.96` (A14), `192.248.0.0` (A15) dengan next hop ke Kalimantan Timur
- Routing subnet `0.0.0.0` (A10) dengan next hop ke Kalimantan

#### KALIMANTAN-TIMUR
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/20aa16f1-e95a-44d9-b3e1-7053668ab556)
- Routing subnet `192.248.21.96` (A14) dan `192.248.0.0` (A15) dengan next hop ke Kalimantan Selatan
- Routing subnet `0.0.0.0` (A12) dengan next hop ke Kalimantan Utara

#### KALIMANTAN-SELATAN
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/7341de1e-2e9f-4d05-9cf1-44642d4ca403)
Kalimantan Selatan yang terhubung ke Kalimantan Timur akan 'meminta' pembagian IP
- `0.0.0.0` dengan next hop ke Kalimantan Timur 

#### SULAWESI
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/61003fcf-4f2a-4210-b4f7-95c7d0d83ccf)
- Routing subnet `192.248.8.0` (A18) dengan next hop ke Maluku Utara
- Routing subnet `192.248.21.0` (A21) dengan next hop ke Belawa
- Routing subnet `192.248.21.168` (A20) dengan next hop ke Makassar
- Routing subnet `0.0.0.0` (A17) dengan next hop ke Jawa

#### MAKASAR
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/74479c2f-cbd3-4df1-91ac-0c0ec4d5bfd7)
`0.0.0.0` dengan next hop ke Sulawesi

#### BELAWA
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/7fb6adbe-9c36-46d5-b401-2b9f393d4bf9)
`0.0.0.0` dengan next hop ke Sulawesi

#### MALUKU-UTARA
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/a74a1fa5-84f5-474b-93c4-d0e3633cb0b8)
`0.0.0.0` dengan next hop ke Sulawesi

### Testing
#### Client to Client
Berawang-Tampu > Ternate
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/dfdf48bb-b324-45fe-8cf2-846ec9dbe1af)

#### Client to Router
Berawang-Tampu > Sulawesi
Starland > Kalimantan-Selatan
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/94edba11-fbf7-433e-8789-c0cd37595165)

#### Router to Router
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/74dcbbcf-d821-4443-a39b-ffbfabcdc155)
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/6f977415-8796-480f-93a1-9ca4f447f8c6)


## GNS3-CIDR
### Routing
#### JAWA
```
auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
	address 192.248.2.164
	netmask 255.255.255.252

auto eth2
iface eth1 inet static
	address 192.248.96.38
	netmask 255.255.255.252

auto eth3
iface eth1 inet static
	address 192.248.178.138
	netmask 255.255.255.252

```

#### SUMATERA
```
auto eth0
iface eth0 inet static
	address 192.248.2.163
	netmask 255.255.255.252
	gateway 192.248.2.164

auto eth1
iface eth1 inet static
	address 192.248.1.159
	netmask 255.255.255.224

auto eth2
iface eth2 inet static
	address 192.248.2.162
	netmask 255.255.255.252
```

#### LAMPUNG
```
auto eth0
iface eth0 inet static
	address 192.248.2.160
	netmask 255.255.255.252
	gateway 192.248.2.162

auto eth1
iface eth1 inet static
	address 192.248.2.159
	netmask 255.255.255.0
```

#### SUMATERA-UTARA
```
auto eth0
iface eth0 inet static
	address 192.248.1.130
	netmask 255.255.255.224
	gateway 192.248.1.159

auto eth1
iface eth1 inet static
	address 192.248.1.129
	netmask 255.255.255.0
```

#### ACEH
```
auto eth0
iface eth0 inet static
	address 192.248.1.127
	netmask 255.255.255.252
	gateway 192.248.1.129

auto eth1
iface eth1 inet static
	address 192.248.0.128
	netmask 255.255.255.128

auto eth2
iface eth2 inet static
	address 192.248.1.127
	netmask 255.255.255.0
```

#### KALIMANTAN-SELATAN
```
auto eth0
iface eth0 inet static
	address 192.248.93.31
	netmask 255.255.255.252
	gateway 192.248.93.32

auto eth1
iface eth1 inet static
	address 192.248.93.0
	netmask 255.255.248.0

auto eth2
iface eth2 inet static
	address 192.248.93.30
	netmask 255.255.255.224
```

#### KALMIANTAN-TIMUR
```
auto eth0
iface eth0 inet static
	address 192.248.95.33
	netmask 255.255.255.252
	gateway 192.248.95.34

auto eth1
iface eth1 inet static
	address 192.248.93.32
	netmask 255.255.248.0

auto eth2
iface eth2 inet static
	address 192.248.95.32
	netmask 255.255.254.0
```

#### KALIMANTAN-SELATAN
```
auto eth0
iface eth0 inet static
	address 192.248.96.35
	netmask 255.255.255.252
	gateway 192.248.96.36

auto eth1
iface eth1 inet static
	address 192.248.95.34
	netmask 255.255.248.0

auto eth2
iface eth2 inet static
	address 192.248.96.34
	netmask 255.255.255.0
```

#### KALIMANTAN
```
auto eth0
iface eth0 inet static
	address 192.248.96.37
	netmask 255.255.255.252
	gateway 192.248.96.38

auto eth1
iface eth1 inet static
	address 192.248.96.36
	netmask 255.255.240.0
```

#### BELAWA
```
auto eth0
iface eth0 inet static
	address 192.248.170.68
	netmask 255.255.255.248
	gateway 192.248.170.72

auto eth1
iface eth1 inet static
	address 192.248.170.64
	netmask 255.255.255.192
```

#### MAKASSAR
```
auto eth0
iface eth0 inet static
	address 192.248.170.69
	netmask 255.255.255.248
	gateway 192.248.170.72
 
auto eth1
iface eth1 inet static
	address 192.248.170.68
	netmask 255.255.255.128
```

#### MALUKU-UTARA
```
auto eth0
iface eth0 inet static
	address 192.248.178.73
	netmask 255.255.255.192
	gateway 192.248.178.136

auto eth1
iface eth1 inet static
	address 192.248.178.72
	netmask 255.255.240.0
```

#### SULAWESI
```
auto eth0
iface eth0 inet static
	address 192.248.178.136
	netmask 255.255.255.252
	gateway 192.248.178.138

auto eth1
iface eth1 inet static
	address 192.248.170.72
	netmask 255.255.255.128

auto eth2
iface eth2 inet static
	address 192.248.178.136
	netmask 255.255.240.0
```
