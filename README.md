# Age Calculator
Proyek **Age Calculator** ini adalah aplikasi sederhana berbasis Java untuk menghitung umur dan menentukan kategori usia berdasarkan tahun kelahiran. Pengguna cukup memasukkan nama dan tahun kelahiran, lalu aplikasi akan menghitung umur dan menampilkan kategori usia berdasarkan tiga kelompok: di bawah umur (< 18 tahun), dewasa (18-60 tahun), atau orang tua (> 60 tahun).

Proyek ini telah di-refactoring menggunakan beberapa teknik refactoring seperti:
- **Extract Method** untuk memisahkan logika input, perhitungan, dan output
- **Rename Method** untuk memperjelas nama metode (seperti `getUserName`, `calculateAge`)
- **Replace Magic Number with Constant** untuk angka-angka dalam penentuan kategori usia
- **Single Responsibility Principle** di mana setiap method memiliki satu tugas spesifik
- **Clean Code Practices** untuk meningkatkan keterbacaan kode

## Fitur Utama
- Input nama pengguna
- Input tahun kelahiran
- Perhitungan umur otomatis
- Penentuan kategori usia dalam tiga kelompok:
  - Di bawah umur (< 18 tahun)
  - Dewasa (18-60 tahun)
  - Orang tua (> 60 tahun)

## Persyaratan
- **Java Development Kit (JDK)** versi 8 atau lebih tinggi harus terinstal di sistem Anda
- Program bisa dijalankan di command line atau IDE Java

## Cara Menjalankan Proyek
### 1. Clone Repositori
Clone repositori proyek ini ke mesin lokal Anda:
```bash
git clone 
```
### 2. Kompilasi Program
Navigasi ke direktori proyek dan kompilasi program:
```bash
javac Demo3/ADafter.java
```
### 3. Jalankan Program
Jalankan program yang telah dikompilasi:
```bash
java Demo3.ADafter
```
## Struktur Program
Program terdiri dari beberapa method utama:
```java
public class ADafter {
    - main(): Method utama untuk menjalankan program
    - getUserName(): Mengambil input nama pengguna
    - getUserBirthYear(): Mengambil input tahun kelahiran
    - calculateAge(): Menghitung usia
    - determineAgeCategory(): Menentukan kategori usia
    - displayResult(): Menampilkan hasil perhitungan
}
```

## Contoh Penggunaan
```
Masukkan nama Anda: 
John Doe
Masukkan tahun lahir Anda: 
1990
Nama Anda adalah John Doe dan umur Anda adalah 34 tahun.
Anda adalah orang dewasa.
```


## Kontribusi
Jika Anda ingin berkontribusi pada proyek ini:
1. Fork repositori
2. Buat branch baru (`git checkout -b fitur-baru`)
3. Commit perubahan (`git commit -m 'Menambah fitur baru'`)
4. Push ke branch (`git push origin fitur-baru`)
5. Buat Pull Request

## Author
Ahmad Nur Mu'minin - 202310370311089

## Lisensi
Proyek ini dibuat untuk tujuan pembelajaran dan tersedia secara open source.i n i   r e a d m e   d a d a k a n 
 
 
