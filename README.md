Tugas 10

1.	Tambahkan fitur Ubah PIN
a.	Tambahkan opsi “Ubah PIN” pada menu utama
b.	Buat mdeo dalam kelas Account untuk mengubah PIN, yaitu: changePin()
c.	Dalam method tersebut lakukan hal berikut:
i.	Verifikasi PIN lama
ii.	Minta nasabah memasukkan PIN baru dua kali
iii.	Validasi bahwa kedua input PIN baru cocok
iv.	Perbarui PIN jika validasi berhasil
Jawab :
![Screenshot (1790)](https://github.com/user-attachments/assets/1b5b278b-85a3-411c-a05c-28575a20598c)
![Screenshot (1791)](https://github.com/user-attachments/assets/0df5807b-47ef-496e-b511-4766d298cab8)

Hasil Run :
![Screenshot (1788)](https://github.com/user-attachments/assets/4426dfb0-a934-4a8e-a4da-1cba06730792)

Penjelasan :
Hasil runningnya merupakan hasil dari menambahkan fitur Ubah Pin pada menu utama dan juga membuat method ChangePin() pada class Account yang di dalamnya terdapat fitur verifikasi pin lama, dan untuk menginput pin baru serta mengonfirmasi pin baru.

2.	Validasi Saldo Minimal pada saat penarikan
a.	Modifikasi fitur penarikan sehingga nasabah harus menyisakan saldo minimal setelah penarikan dilakukan. Misal, saldo minial adalah Rp50,000-
b.	Langkah-langkah:
i.	Tentukan saldo minimal, tambahkan konstanta MINIMUM_BALANCE dalam kelas Account
ii.	Modifikasi methode execute() dalam kelas Withdrawal untuk memeriksa apakah saldo setelah penarikan tidak kuran dari saldo minimal
iii.	Jika saldo tidak mencukupi, tampilkan pesan kesalahan
Jawab :
![Screenshot (1792)](https://github.com/user-attachments/assets/f55891e5-a188-43b0-92c1-84fb214bacef)
![Screenshot (1793)](https://github.com/user-attachments/assets/f730c42d-2e7e-4830-b7f0-d85c746afc19)

Hasil Run :
![Screenshot (1789)](https://github.com/user-attachments/assets/86f81a28-960e-44f3-9a0e-59d800531905)

Penjelasan :
Hasil runningnya merupakan hasil dari memodifikasi fitur penarikan dengan menambahkan public static final double MINIMUM_BALANCE dalam class Account dan memodifikasi method execute() dalam class Withdrawal untuk mendetect agar saldo pada rekening tidak habis, atau menyisakan 50000 saldo.
