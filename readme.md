<h1 align="center">Selamat datang di KelasKita! 👋</h1>

### 🤨 Fitur apa saja yang tersedia di KelasKita?
- Autentikasi Admin
- List Siswa & CRUD
- User & CRUD
- Jadwal piket & CRUD
- Jadwal Pelajaran & CRUD
- Settings (Dapat mengubah data website seperti judul, logo, favicon, dll)
- Artikel
- Dan lain-lain


 ### 👤 Default Account for testing
	
**Admin Default Account**
- Username: admin
- Password: admin

------------

## 💻 Install

1. **Clone Repository**
```bash
git clone https://github.com/zuramai/kelaskita.git
cd kelaskita
composer install
npm install
copy .env.example .env
```

2. **Buka ```.env``` lalu ubah baris berikut sesuai dengan databasemu yang ingin dipakai**
```
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```

3. **Instalasi website**
```bash
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan storage:link
```

4. **Jalankan website**
```bash
php artisan serve
```


## 🤝 Contributing
Contributions, issues and feature requests di persilahkan.
Jangan ragu untuk memeriksa halaman masalah jika Anda ingin berkontribusi. **Berhubung Project ini saya sudah selesaikan sendiri, namun banyak fitur yang kalian dapat tambahkan silahkan berkontribusi yaa!**


## 📝 License
- **KelasKita is open-sourced software licensed under the MIT license.**

------------

- Thanks to <a href="https://devover.or.id">DevoverID</a>
- KelasKita is open-sourced software licensed under the MIT license.

