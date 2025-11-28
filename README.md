**Cara Penggunaan:**
**Ganti variabel** sesuai dengan setup Anda:

1. VPN_SERVER_IP - IP server VPN

192.168.1.1 - Gateway ISP1

192.168.2.1 - Gateway ISP2

pptp-out1 - Nama interface VPN

**Pastikan:**

Kedua ISP terkoneksi dengan baik

Routing dasar sudah berfungsi

VPN connection sudah terkonfigurasi

Test failover dengan mematikan koneksi ISP1

Script ini akan secara otomatis mendeteksi jika ISP utama down dan berpindah ke ISP backup, kemudian kembali ke ISP utama ketika sudah normal.
