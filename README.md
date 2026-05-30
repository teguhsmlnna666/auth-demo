Laravel Authentication & Breeze

Implementasi sistem autentikasi menggunakan Laravel Breeze pada framework Laravel

Fitur:
1. Registrasi Pengguna
2. Login dan Logout
3. Halaman Dashboard
4. Edit Profil
5. Halaman Admin

Instalasi Project:
1. Teknologi yang digunakan:
    - Laravel 12++
    - PHP 8.2
    - MySQL
    - Laravel Breeze
2. Clone Repository
    https://github.com/teguhsmlnna666/auth-demo -> code -> Https
3. Buka terminal dan jalankan perintah berikut:
    git clone https://github.com/teguhsmlnna666/auth-demo.git
4. Masuk ke folder Project
5. Install Dependency dengan perintah berikut:
    ```bash
    composer install
    npm install
    ```
6. Buat file .env dengan perintah berikut:
    ```bash
    copy .env.example .env
    ```
7. Generate key dengan perintah berikut:
    ```bash
    php artisan key:generate
    ```
8. Buat database pada phpMyAdmin
    misalnya: auth_demo
9. Konfigurasi database pada file .env menjadi seperti berikut:
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=auth_demo
    DB_USERNAME=root
    DB_PASSWORD=
10. Jalankan Migration dengan perintah berikut:
    ```bash
    php artisan migrate
    ```
11. Jalankan aplikasi (buka 2 terminal terpisah):
    Terminal 1:
    ```bash
    npm run dev
    ```
    Terminal 2:
    ```bash
    php artisan serve
    ```
12. Akses halaman aplikasi pada browser dengan link berikut: http://127.0.0.1:8000
13. Jika ingin akses halaman admin, ganti role user menjadi admin pada tabel user melalui phpMyAdmin.
    Akses link berikut untuk membuka halaman admin: http://127.0.0.1:8000/admin

