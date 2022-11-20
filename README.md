

## *:information_source: Inventoryweb*
Source Code ini merupakan starter dari Framework `Laravel` yang sudah ada fitur `Login dengan role user yang berbeda serta menu yang bisa di tambah atau di hapus sesuai kebutuhan kita dan juga bisa mengatur akses menu apa saja yang ingin di tampilkan berdasarkan role.` Alasan saya membuat starter Laravel tersebut `untuk mempercepat proses pembuatan sebuah aplikasi berbasis web` agar bisa menghemat beberapa waktu pengerjaanya.
<br><br>
Untuk tampilannya saya sudah pasang template admin `bootstrap v5` yaitu `sash admin`.

## *:sparkles: Fitur*
* **Login**
* **Menu** `Create`, `Read`, `Update`, `Delete`
* **Role** `Create`, `Read`, `Update`, `Delete`
* **User** `Create`, `Read`, `Update`, `Delete`
* **Hak Akses** `Mengatur Hak Akses Menu berdasarkan Role User`
* **Pengaturan Website** `Merubah Profil Website`

## *:electric_plug: Plugin*
* **Yajra Datatables**
* **SweetAlert**
* **jQuery**
* **dan banyak lagi..**

## *:gear: Requirement*
<p>
<img alt="gambar" src="https://img.shields.io/badge/PHP%20-%5E8.1-green"/>
<img alt="gambar" src="https://img.shields.io/badge/Node JS%20-%5E16.14.0-green"/>
<img alt="gambar" src="https://img.shields.io/badge/Npm%20-%5E8.3.1-green"/>
<img alt="gambar" src="https://img.shields.io/badge/Composer%20-%5E2.3.9-green"/>
</p>

## *:rocket: Instalasi*
#### :arrow_right: Buat Database
Buat Database `db_laravel9`
#### :arrow_right: Config ENV
Ubah file dari `env.development` jadi `.env`
#### :arrow_right: Set Up
Buka Terminal di proyek folder Anda dan jalankan perintah dibawah ini:
```
composer install
```
```
php artisan migrate
```
```
php artisan db:seed
```
```
import file database ke phpmyadmin yang ada di folder database/db
```
```
php artisan storage:link
```
#### :arrow_right: Jalankan Aplikasi
```
php artisan serve
```
copy & paste `http://127.0.0.1:8000/` ke browser anda.

#### :arrow_right: Login Default
username: `superadmin` password: `12345678`
<br>
username: `admin` password: `12345678`
<br>
username: `operator` password: `12345678`

## *:desktop_computer: Preview*
![ad3c121d-1c33-4b7f-aa0f-5bb2ddce7cf6](https://user-images.githubusercontent.com/47371845/202890250-2c1e64c6-cc01-453f-b490-43eecab1e153.png)



