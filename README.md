# 🚗 Bengkel Maju Mundur

Aplikasi sistem manajemen bengkel berbasis Laravel.

---

## 📌 Fitur Utama
- CRUD Produk
- Manajemen Stok Barang
- Sistem Inventaris
- Tampilan berbasis Bootstrap

---

## 🛠️ Teknologi
- PHP (Laravel)
- MySQL
- Bootstrap 5

---

## ⚙️ Cara Install

```bash
git clone https://github.com/ilhamjhi/bengkel_maju_mundur.git
cd bengkel_maju_mundur
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve