# Tutorial Instalasi Aplikasi SIAK Modul Kurikulum
Untuk menggunakan 
# Tutorial Pemakaian Aplikasi SIAK Modul Kurikulum
Aplikasi SIAK untuk modul kurikulum terdapat 2 peran yaitu admin dan admin-kurikulum admin dapat melakukan CRUD terhadap Universitas, Mata Kuliah, dan Prodi. Sedangkan pada admin-kurikulum dapat melakukan CRUD terhadap Kurikulum, Mata Kuliah dan Prasyaratnya.

## Login
![](https://s29.postimg.org/4v05z5x07/login.png)
Login pada aplikasi untuk masuk ke phome page.
**user admin**
*ID USER : admin*
*PASS : admin*
**user admin-kurikulum**
*ID USER : admin-kurikulum*
*PASS : admin-kurikulum*

## Halaman Admin
### Home page
[![home-admin.png](https://s24.postimg.org/xsf6j28sl/home_admin.png)](https://postimg.org/image/hhf2mqwap/)
gambar diatas adalah tampilan home untuk admin. Untuk mengelola universitas klik pada menu pojok kiri atas **kelola universitas**
### kelola Universitas, Fakultas, dan Prodi
[![kelola-univ1.png](https://s23.postimg.org/x7u00del7/kelola_univ1.png)](https://postimg.org/image/hmcogf2mv/)
Gambar diatas adalah halaman untuk kelola universitas. Untuk menambahkan universitas gunakan panel sebelah kanan isi nama universitas dan tambahkan. Untuk edit klik pada column action pada icon edit untuk mengedit universitas. Untuk melihat **Fakultas** yang dimiliki oleh universitas, klik icon eye pada column action.

Untuk kelola Fakultas dan Prodi sama dengan kelola Universitas.
[![kelola-fakultas.png](https://s27.postimg.org/nlrphyrer/kelola_fakultas.png)](https://postimg.org/image/audjbghmn/)
[![Kelola-prodi.png](https://s23.postimg.org/405t7zexn/Kelola_prodi.png)](https://postimg.org/image/yud25pkk7/)

## Halaman Admin-Kurikulum
### Home page
[![home-admin-kurikulum.png](https://s29.postimg.org/joch7mpw7/home_admin_kurikulum.png)](https://postimg.org/image/e066gqljn/)
gambar diatas adalah tampilan home untuk admin-kurikulum. Untuk mengelola kurikulum klik pada menu pojok kiri atas **kelola Kurikulum**
### Halaman Kelola Kurikulum
[![kelola-kurikulum.png](https://s23.postimg.org/yilrpxky3/kelola_kurikulum.png)](https://postimg.org/image/7kruo70av/)
Untuk pengelolaan kurikulum hampir sama dengan pengelolaan pada universitas. Bedanya hanya ada pada saat pertama kali mencari kurikulum dimana user harus memilih universitas, fakultas, dan prodi. Serta untuk prasyarat hanya ada pilihan untuk menghapus dan menambahkan.
[![Kelola-MAtkul.png](https://s27.postimg.org/h7t291w2b/Kelola_MAtkul.png)](https://postimg.org/image/w3rlgn7gv/)
[![Kelola-prasyarat.png](https://s30.postimg.org/k2z6203td/Kelola_prasyarat.png)](https://postimg.org/image/czramdydp/)

## API
Modul Kurikulum membuat beberapa REST api yang dapat diakses secara umum. Aturan alamat rest api sebagai berikut
*/kurikulum/services/{tag}/{method}*

list tag :
* **univ** - untuk universitas
* **fakultas** - untuk fakultas
* **prodi** - untuk prodi
* **kurikulum** - untuk kurikulum
* **matkul** - untuk matkul

list method :
* **all** - untuk ambil seluruh objek
* **id/{id}** - untuk ambil spesifik objek dengan ID.














