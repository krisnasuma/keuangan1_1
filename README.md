# Keuangan1_1

Pastikan Python sudah terinstal, lalu instal Django menggunakan pip:
<br>
>pip install django

Kemudian akses folder projek dengan command line sampai menemukan file yang bernama "manage", lalu jalankan perintah: 
<br>
>python manage.py runserver

Akses urls Web
* Panel admin: http://127.0.0.1:8000/admin/
* Tampilan transaksi: http://127.0.0.1:8000/transaksi/
* Tampilan add transaksi tanpa perantara admin: http://127.0.0.1:8000/transaksi/tambah/
* Ekspor CSV: http://127.0.0.1:8000/transaksi/ekspor-csv/

<br>
username: admin
<br>
password: admin

# Fitur
Fitur Lanjutan
<br>
1. Grafik dan Visualisasi Data
* Menampilkan grafik tren pemasukan dan pengeluaran.
* Menggunakan library Chart.js.

2. Kategori Transaksi
* Menambahkan formulir "kategori" untuk mengelompokkan transaksi pada tampilan Input Transaksi.
* Menampilkan ringkasan keuangan berdasarkan kategori.


# Tampilan

![Sample Image](https://github.com/krisnasuma/keuangan1_1/blob/main/tampilanhalamantransaksiV1_1.PNG)

![Sample Image](https://github.com/krisnasuma/keuangan1_1/blob/main/tampilanhalamantransaksiGrafikV1_1.PNG)

![Sample Image](https://github.com/krisnasuma/keuangan1_1/blob/main/tampilantambahtransaksiaAddCategoryFormsV1_1.PNG)

![Sample Image](https://github.com/krisnasuma/keuangan1_1/blob/main/HasilFiturExsportCSV.PNG)

# Versi Sebelumnya
* V0: https://github.com/krisnasuma/keuangan/
* V1: https://github.com/krisnasuma/keuangan1
