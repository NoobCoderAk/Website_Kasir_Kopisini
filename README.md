<p align="center">
    <a href="https://github.com/NoobCoderAk" target="_blank"><img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fid.m.wikipedia.org%2Fwiki%2FBerkas%3ALaravel.svg&psig=AOvVaw36oodaBV5RYV2HLrs6fPS6&ust=1672844244910000&source=images&cd=vfe&ved=0CBAQjRxqFwoTCNiy_8nUq_wCFQAAAAAdAAAAABAE" width="120"></a>
</p>

## Instalasi
#### Via Git
```bash
git clone https://github.com/sandinur157/tuturial-membuat-aplikasi-point-of-sales.git
```

### Setup Aplikasi
Jalankan perintah 
```bash
composer update
```
atau:
```bash
composer install
```
Copy file .env dari .env.example
```bash
cp .env.example .env
```
Konfigurasi file .env
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=example_app
DB_USERNAME=root
DB_PASSWORD=
```
Opsional
```bash
APP_NAME=Laravel
APP_ENV=local
APP_KEY=base64:QGRW4K7UVzS2M5HE2ZCLlUuiCtOIzRSfb38iWApkphE=
APP_DEBUG=true
APP_URL=http://example-app.test
```
Generate key
```bash
php artisan key:generate
```
Migrate database
```bash
php artisan migrate
```
Seeder table User, Pengaturan
```bash
php artisan db:seed
```
Menjalankan aplikasi
```bash
php artisan serve
```

## Link Tutorial

- [Youtube](https://www.youtube.com/playlist?list=PLaN75JfoGz0Okf9f_7GbGM5IFaLXWx-_C)
- [W2Learn](https://www.w2learn.com)

## License

[MIT license](https://opensource.org/licenses/MIT)
