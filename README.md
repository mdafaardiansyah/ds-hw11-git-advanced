# ds-hw10-git-scm
Digital Skola Homework ke 10 - Git & Source Code Management

## Langkah Pengerjaan dan Penjelasannya

1. **Clone repository dari GitHub**
   ```bash
   git clone git@github.com:mdafaardiansyah/ds-hw10-git-scm.git
   ```
   *Perintah ini digunakan untuk menyalin seluruh isi repository dari GitHub ke komputer lokal Anda.*

2. **Masuk ke direktori hasil clone**
   ```bash
   cd ds-hw10-git-scm
   ```
   *Perintah ini memindahkan Anda ke folder project yang baru saja di-clone.*

3. **Membuat file baru bernama `test1.txt`**
   ```bash
   echo "Ini adalah isi file test1.txt" > test1.txt
   ```
   *Perintah ini membuat file baru bernama `test1.txt` dan mengisinya dengan teks.*

4. **Mengecek status repository**
   ```bash
   git status
   ```
   *Digunakan untuk melihat status perubahan di repository, seperti file baru atau file yang diubah.*

5. **Menambahkan file baru ke staging area**
   ```bash
   git add .
   ```
   *Perintah ini menambahkan semua perubahan (file baru/diubah) ke staging area agar siap di-commit.*

6. **Mengecek kembali status repository**
   ```bash
   git status
   ```
   *Untuk memastikan file sudah masuk ke staging area sebelum commit.*

7. **Commit perubahan dengan pesan**
   ```bash
   git commit -m "Menambahkan file test1.txt"
   ```
   *Commit digunakan untuk menyimpan snapshot perubahan ke repository lokal. Pesan commit sebaiknya menjelaskan perubahan yang dilakukan.*

8. **Push commit ke repository GitHub**
   ```bash
   git push origin main
   ```
   *Perintah ini mengirimkan commit dari repository lokal ke repository remote (GitHub).*
   - **origin**: Nama default untuk remote repository (dalam hal ini GitHub).
   - **main**: Nama branch utama pada repository.

---

Made by ***Dapuk***
