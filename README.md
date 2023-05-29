# pertemuan10_semester2

```s
NAMA    : ALIYAH ASMARANI
NIM     : 312210203
KELAS   : TI.22.A.2
MATKUL  : BASIS DATA
```

## PRAKTIKUM 1 (PEGAWAI)

### Buat Table Pegawai
![table](https://github.com/Aliyahasmarani/pertemuan10_semester2/assets/115197672/be9bfa47-3c6b-43f8-a4c1-593e4625efac)

### Tampilkan pegawai yang gajinya bukan 2.000.000 dan 1.250.000!
![table1](https://github.com/Aliyahasmarani/pertemuan10_semester2/assets/115197672/6d44b0f0-dd10-4f87-9474-4e94f525f358)

  Dalam contoh diatas, 'pegawai' adalah nama tabel yang berisi data pegawai, dan 'gaji' adalah kolom yang menyimpan informasi gaji. Klausa WHERE digunakan untuk memfilter baris-baris yang memenuhi kondisi tertentu. 
  Klausa NOT IN digunakan untuk memeriksa apakah gaji tidak sama dengan 2.000.000 atau 1.250.000. Dalam contoh praktikum ini, pegawai dengan gaji 2.000.000 dan 1.250.000 akan dikecualikan dari hasil yang ditampilkan.

### Tampilkan pegawai yang tunjangannya NULL!
![table2](https://github.com/Aliyahasmarani/pertemuan10_semester2/assets/115197672/71fd43ef-5357-43ae-b430-c8ddb31c1d34)

  Dalam contoh diatas, 'pegawai' adalah nama tabel yang berisi data pegawai, dan 'tunjangan' adalah kolom yang menyimpan informasi tunjangan. Klausa WHERE digunakan untuk memfilter baris-baris yang memenuhi kondisi tertentu.
  Klausa IS NULL digunakan untuk memeriksa apakah nilai tunjangan adalah NULL. Dalam contoh praktikum ini, hanya pegawai dengan tunjangan NULL yang akan ditampilkan dalam hasil.

### Tampilkan pegawai yang tunjangannya tidak NULL!
![table3](https://github.com/Aliyahasmarani/pertemuan10_semester2/assets/115197672/694893c8-d169-4e4b-b725-2c004282d2da)

  Dalam contoh diatas, 'pegawai' adalah nama tabel yang berisi data pegawai, dan 'tunjangan' adalah kolom yang menyimpan informasi tunjangan. Klausa WHERE digunakan untuk memfilter baris-baris yang memenuhi kondisi tertentu.
  Klausa IS NOT NULL digunakan untuk memeriksa apakah nilai tunjangan tidak NULL. Dalam contoh praktikum ini, hanya pegawai dengan tunjangan yang tidak NULL yang akan ditampilkan dalam hasil.
 
### Tampilkan/hitung jumlah baris/record tabel pegawai!
![table4](https://github.com/Aliyahasmarani/pertemuan10_semester2/assets/115197672/3bbc5014-5ebc-4000-b5af-8a50c46858c0)

  Dalam contoh diatas, saya menggunakan fungsi COUNT() untuk menghitung jumlah baris atau record dalam tabel "pegawai'. Fungsi COUNT( * ) digunakan untuk menghitung semua semua baris dalam tabel.
  perintah diatas akan menghasilkan satu kolom dengan nama "jumlah_pegawai" yang akan berisi jumlah baris atau record dalam tabel "pegawai".

### Tampilkan/hitung jumlah total gaji di tabel pegawai!
![table5](https://github.com/Aliyahasmarani/pertemuan10_semester2/assets/115197672/2145490a-f17f-4177-bcec-f228291e3b44)

  Dalam contoh di atas, saya menggunakan fungsi agregat SUM() untuk menghitung jumlah total gaji dalam tabel "pegawai". Fungsi SUM() digunakan untuk menjumlahkan nilai dalam kolom "gaji".

### Tampilkan/hitung rata-rata gaji pegawai!
![table6](https://github.com/Aliyahasmarani/pertemuan10_semester2/assets/115197672/dc7b7372-f26c-48e6-8d99-03e1e1507d23)

  Di atas, saya menggunakan fungsi agregat AVG() untuk menghitung rata-rata gaji pegawai dalam tabel "pegawai". Fungsi AVG() digunakan untuk menghitung nilai rata-rata dari nilai dalam kolom "gaji".

### Tampilkan gaji terkecil!
![table7](https://github.com/Aliyahasmarani/pertemuan10_semester2/assets/115197672/c9b2eeb1-76fe-4ab9-93c6-fed1cbd450ef)

  Diatas, saya menggunakan fungsi agregat MIN() untuk mencari gaji terkecil dalam kolom "gaji" dalam tabel "pegawai".

### Tampilkan gaji terbesar!
![table8](https://github.com/Aliyahasmarani/pertemuan10_semester2/assets/115197672/bf652da1-53a5-4fab-b9a4-55b73379a3f6)

   Di atas, saya menggunakan fungsi agregat MAX() untuk mencari gaji terbesar dalam kolom "gaji" dalam tabel "pegawai".
  


