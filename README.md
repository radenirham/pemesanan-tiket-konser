# pemesanan-tiket-konser
Aplikasi pemesanan tiket konser

**Admin Default Account**

-   username: admin
-   Password: admin123

**User Default Account**
-   username: user1
-   Password: user12345
---

## Install

1. **Clone Repository**

```bash
git clone https://github.com/radenirham/pemesanan-tiket-konser.git
cd Ticket-Laravel
composer install
cp .env.example .env
```

2. **Buka `.env` lalu ubah baris berikut sesuai dengan database yang ingin dipakai**

```bash
DB_PORT=3306
DB_DATABASE=ticketonline
DB_USERNAME=root
DB_PASSWORD=
```

3. **Instalasi website**

```bash
php artisan key:generate
php artisan migrate --seed
```

4. **Jalankan website**

```bash
php artisan serve
