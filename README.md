<h1 align="center">Selamat datang di Proyek 1 Apotek Kami! 👋</h1>

## Apa itu Apotek?

Web Apotek yang dibuat oleh <a href="https://github.com/judhacdc"> Judha Maygustya </a>. **Apotek adalah aplikasi manajemen Apotek melalui website dengan mudah.**

## Fitur apa saja yang tersedia di Laundry?

-   Autentikasi Admin
-   Category & CRUD
-   Member & CRUD
-   User & CRUD
-   Promo
-   Apotek
-   Dan lain-lain

## Release Date

**Release date : 14 Mei 2022**


---

## Default Account for testing

**Admin Default Account**

-   Username: admin
-   Password: admin

**Operator Default Account**

-   Username: operator
-   Password: operator

---

## Install

1. **Clone Repository**

```bash
git clone https://github.com/judhacdc/Proyek1_Apotek.git
cd Laundry-Laravel-Vue
composer install
npm install
cp .env.example .env
```

2. **Buka `.env` lalu ubah baris berikut sesuai dengan databasemu yang ingin dipakai**

```bash
DB_PORT=3306
DB_DATABASE=apotek
DB_USERNAME=root
DB_PASSWORD=
```

3. **Instalasi website**

```bash
php artisan key:generate
php artisan migrate --seed
php artisan jwt:secret
php artisan config:cache
```

4. **Jalankan website**

```bash
php artisan serve
```

## Contributing

Contributions, issues and feature requests di persilahkan.
Jangan ragu untuk memeriksa halaman masalah jika Anda ingin berkontribusi. **Berhubung Project ini saya sudah selesaikan sendiri, namun banyak fitur yang kalian dapat tambahkan silahkan berkontribusi yaa!**

## License

-   Copyright © 2022 Judha Maygustya.
