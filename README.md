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
### Pembagian IP -VLSM
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/02c603cc-1c6d-48b5-89c0-8e3c0893f9f3)

### Tree -VLSM
Subnet besar yang dibentuk memiliki network ID 192.248.0.0 dengan netmask /19, sehingga didapatkan pembagian IP sebagai berikut
![VLSM_Tree_IT30](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/abfcc842-1d6f-4128-bc7d-4615cfc58a89)

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
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/17aea317-36f1-4789-b9fb-62b74409f73a)

#### SUMATERA
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/55f6b3ee-d453-4592-8c54-08ecc23fd195)

#### SUMATERA-UTARA
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/b303762b-8ca9-46eb-8851-30b4774963c1)

#### ACEH
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/0adb32c4-4c97-4494-8e16-f8a5121bfcbf)

#### LAMPUNG
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/8e1dc91d-01e3-4471-80f6-0308bd063cd2)

#### KALIMANTAN
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/5db6edf9-836d-4e85-98a1-e0498ede0072)

#### KALIMANTAN-UTARA
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/6cc92dea-3284-433e-98ce-9dc587837198)

#### KALIMANTAN-TIMUR
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/cd5a6630-a9fa-4955-8124-8eab81c19e19)

#### KALIMANTAN-SELATAN
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/3cf60b14-47ed-4593-8991-c54484d9cd79)

#### SULAWESI
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/b8ff4cbe-88a6-4114-9590-aea075d8b8bc)

#### MAKASAR
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/4f761011-c49c-4f54-a242-a1989a9a51a7)

#### BELAWA
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/fa442950-c6ed-4829-8a76-cd9311d07d2e)

#### MALUKU-UTARA
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/0fe9a220-b822-4253-aeeb-3c866e3de7e9)

### Testing
Baru > Sebuku
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/0f8bbb0c-ba83-4902-8f40-f54b3e90e276)

Berawang-Tampu > Tobelo
![image](https://github.com/GabriellaErlinda/Jarkom-Modul-4-IT30-2024/assets/128443451/696fee75-a952-4875-9ba3-70752a55ce07)

