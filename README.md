# laravel-docker-8-to-9
Update laravel docker 8 to 9

## Setup Depedencies
1. Update versi php dan dependencies ```composer.json``` silahkan cek https://github.com/niomictomi/upgrade-laravel8-to-laravel9
2. Jika berhasil, silahkan ke tahap selanjutnnya.

## Update Docker Environments
1. Environment docker laravel kali ini terdiri dari container ```app```, ```node```, ```db``` dan ```nginx```. Kurang lebih seperti pada https://github.com/niomictomi/Laravel-Docker .
2. Kita akan berfokus pada container ```app```, yaitu kontaier yang berisi file-file dari Framwork laravel.
3. Pada konfigurasi file docker, silahkan sesuaika versi PHP untuk Laravel 9, yaitu minimal PHP versi 8.0.2.
4. Masuk ke container ```app```, kemudikan jalankan ```composer update```
5. Jika tidak ada error, maka silahkan cek versi laravel dengan command ```php artisan --version```
6. Selesai
