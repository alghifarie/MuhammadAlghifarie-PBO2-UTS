# MuhammadAlghifarie-PBO2-UTS
Here's a basic README file for your `BukuAlamat` application:

---

# BukuAlamat - Aplikasi Buku Alamat

BukuAlamat adalah aplikasi desktop berbasis Java yang digunakan untuk mengelola data alamat seperti nama, alamat, dan nomor telepon. Aplikasi ini menyediakan fitur untuk menambah, mengedit, menghapus, dan mencari data alamat yang disimpan dalam file CSV.

## Fitur Utama
- **Menambah Data**: Pengguna dapat memasukkan nama, alamat, dan nomor telepon, lalu menyimpannya dalam tabel dan file CSV.
- **Mengedit Data**: Pengguna dapat memilih data yang ada dan melakukan perubahan (edit).
- **Menghapus Data**: Pengguna dapat menghapus data yang dipilih dari tabel dan file CSV.
- **Mencari Data**: Pengguna dapat mencari data berdasarkan nama, alamat, atau nomor telepon.
- **Simpan & Muat dari CSV**: Semua data disimpan dalam file `data_alamat.csv` yang dapat dimuat kembali saat aplikasi dibuka.

## Prasyarat
- **Java Development Kit (JDK)** versi 8 atau lebih baru.
- **IDE** seperti IntelliJ IDEA, Eclipse, atau NetBeans untuk memudahkan pengembangan.

## Cara Menjalankan Aplikasi
1. **Unduh atau Clone Repository**: 
   Jika kamu mengunduh atau melakukan clone dari repository, pastikan kamu sudah memiliki file `data_alamat.csv` di direktori yang sama dengan aplikasi jika ingin data tersimpan dan dimuat dengan benar.

2. **Kompilasi dan Jalankan**:
   - Buka file `BukuAlamat.java` dalam IDE pilihanmu.
   - Kompilasi dan jalankan aplikasi dengan menekan tombol "Run".

3. **Interaksi dengan Aplikasi**:
   - Setelah aplikasi berjalan, kamu dapat mulai memasukkan data alamat pada form yang tersedia.
   - Data yang dimasukkan akan langsung tersimpan pada tabel dan file `data_alamat.csv`.
   - Gunakan fitur pencarian untuk menemukan data yang diinginkan.
   - Pilih data untuk mengedit atau menghapusnya.

## Struktur Direktori
```
/BukuAlamat
  /src
    BukuAlamat.java       # Kode sumber utama aplikasi
  /data
    data_alamat.csv       # File CSV untuk menyimpan data alamat
  /README.md              # File README ini
```

## Penjelasan Kode
1. **BukuAlamat.java**:
   - Kode utama aplikasi yang mengelola antarmuka pengguna dan interaksi dengan file CSV.
   - Memuat data dari `data_alamat.csv` saat aplikasi dijalankan dan menyimpannya kembali ketika data diperbarui.
   
2. **Fungsi Utama**:
   - `loadCSV()`: Memuat data alamat dari file CSV.
   - `simpanKeCSV()`: Menyimpan data ke file CSV setelah perubahan.
   - `btnSimpanActionPerformed()`: Menambahkan data baru ke dalam tabel dan file CSV.
   - `btnEditActionPerformed()`: Mengedit data yang sudah ada.
   - `btnHapusActionPerformed()`: Menghapus data yang dipilih.
   - `btnCariActionPerformed()`: Mencari data berdasarkan input pencarian.

