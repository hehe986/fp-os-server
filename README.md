
# PROJECT-OS-SERVER-&-SYSTEM-ADMIN
Tema : Web Server Jual Jasa Custom

## Dibuat
- M. Ardita Hilmi (23.83.0981)

## Spesifikasi Ubuntu Server
- RAM 8 GB
- Storage 15 GB
- Ubuntu Server 24.04.1

## Layanan yang digunakan
| Jenis Layanan           | Layanan Server              |
| :--------               | :-------                 |
| `Web Server`            | `Apache2`                |
| `Database Server`       | `MySQL`                  |
| `SSH Server`            | `OpenSSH`                |
| `Data Structure Server` | `OpenSSH`                |
| `Monitoring`            | `Prometheus dan Grafana` |

## Langkah-Langkah
## Langkah-Langkah
## 1.OpenSSH
 ![Logo](apache2.jpg)

### Install OpenSSH
```bash
sudo apt update && sudo apt install openssh-server  -y
```
### Memulai layanan SSH
```bash
sudo service ssh start
```
### Melihat status layanan SSH
```bash
sudo service ssh status
```
### Menginstal net-tools
```bash
sudo apt install net-tools -y
```

## 2. Apache2
 ![Logo](apache2.jpg)

### Install Apache2
```bash
sudo apt update && sudo apt install apache2  -y
```
