
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
 ![Logo](ssh.jpg)

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

### Memperbarui dan Install Apache2
```bash
sudo apt update && sudo apt install apache2  -y
```
### cek status Apache2
```bash
sudo service apache2 status
```
### cek available aplikasi Apache2
```bash
sudo ufw app list
```
### port Apache2
```bash
sudo ufw app info "Apache Full"
```
### cek status Apache2
```bash
sudo ufw status
```

## 3. MySQL dan PHP
 ![Logo](apache2.jpg)

### Install MySQL dan server
```bash
sudo apt install php libapache2-mod-php php-mysql mysql-server -y 
```
### Install phpmyadmin -y
```bash
sudo apt install phpmyadmin -y
```
### Package configuration
 ![logo](1.jpg)
 ![Logo](2.jpg)
 ![Logo](3.jpg)

### PHP file
```bash
 sudo nano /etc/apache2/mods-enabled/dir.conf
```
![dir.conf](2.jpg)

### PHP file
```bash
 sudo nano /etc/apache2/mods-enabled/dir.conf
```

### Konfigurasi Koneksi Database
```bash
 sudo nano /etc/phpmyadmin/config-db.php
```
![isiconfig-db](2.jpg)

### Membuat symlink ke folder phpMyAdmin
```bash
sudo ln -s /usr/share/phpmyadmin /var/www/html/phpmyadmin
```

### Masuk mysql
```bash
sudo mysql -u root -p
```
![009](2.jpg)

### Masuk mysql
```bash
sudo nano /var/www/html/submit_order.php
```
![011](2.jpg)

