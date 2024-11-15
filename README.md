
cekNomorGenalGanjil

Nama: Rafi Rizqullah
NPM: 2210010288
Kelas: 5A REG BJB

memiliki program yang dapat mendeteksi genap ganjil dan variasi lengkap seperti bilangan prima

# Cek Nomor Frame - Aplikasi untuk Mengecek Angka

Aplikasi ini menggunakan Java Swing untuk membuat antarmuka grafis yang memungkinkan pengguna untuk memeriksa dua hal mengenai sebuah angka:

1. **Apakah angka tersebut genap atau ganjil?**
2. **Apakah angka tersebut bilangan prima?**

## Deskripsi Program

Program ini menggunakan `JTextField` untuk menerima input angka dari pengguna dan tombol `cek` untuk memulai proses pengecekan. Setelah pengguna memasukkan angka dan menekan tombol `cek`, hasil pengecekan akan ditampilkan dalam jendela pesan.

### Fitur:
- **Pengecekan Angka Genap/Ganjil:** Menggunakan operator modulus untuk menentukan apakah angka yang dimasukkan genap atau ganjil.
- **Pengecekan Bilangan Prima:** Menggunakan loop untuk memeriksa apakah angka adalah bilangan prima, yaitu angka yang hanya dapat dibagi oleh 1 dan dirinya sendiri.
- **Validasi Input:** Program memeriksa apakah input yang dimasukkan adalah angka. Jika bukan angka, maka akan muncul pesan kesalahan.

## Cara Penggunaan

1. **Masukkan angka** pada kolom input yang disediakan.
2. **Klik tombol "cek"** untuk memulai pengecekan.
3. Program akan menampilkan hasil berupa:
   - **Genap/Ganjil** sesuai dengan angka yang dimasukkan.
   - **Bilangan Prima atau Bukan** sesuai dengan hasil pemeriksaan angka tersebut.

### Contoh:
- Jika pengguna memasukkan angka `7`, program akan menunjukkan bahwa `7` adalah **Ganjil** dan **Bilangan Prima**.
- Jika pengguna memasukkan angka `10`, program akan menunjukkan bahwa `10` adalah **Genap** dan **Bukan Bilangan Prima**.

## Struktur Kode

Aplikasi ini menggunakan beberapa komponen Java Swing sebagai berikut:
- **`JTextField`:** Untuk menerima input angka dari pengguna.
- **`JButton`:** Untuk memicu pengecekan angka.
- **`JLabel`:** Untuk menampilkan hasil pengecekan.
- **`JOptionPane`:** Untuk menampilkan hasil pengecekan dalam jendela dialog.

### Catatan:
- Program ini hanya menerima input angka. Jika input tidak valid (misalnya huruf atau simbol), program akan menampilkan pesan kesalahan.
- Aplikasi ini juga hanya mendukung bilangan bulat (integer).

## Instalasi

1. Pastikan Anda telah menginstal Java Development Kit (JDK) pada komputer Anda.
2. Salin kode sumber ke dalam IDE Java (misalnya IntelliJ IDEA atau NetBeans).
3. Jalankan program untuk melihat antarmuka dan fitur-fitur yang ada.

## Lisensi

Program ini dilisensikan di bawah lisensi MIT - lihat file LICENSE untuk informasi lebih lanjut.

![image](https://github.com/user-attachments/assets/76116986-e388-4e88-9f19-487d19d37c2a)

