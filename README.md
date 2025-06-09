# ds-hw11-git-advanced
Digital Skola Homework ke 11 - Git Advanced & Tagging

## Langkah Pengerjaan dan Penjelasannya

1. **Membuat dan berpindah ke branch baru `dev`**
   ```bash
   git checkout -b dev
   ```
   *Perintah ini membuat branch baru bernama `dev` dan langsung berpindah ke branch tersebut.*

2. **Cek branch yang aktif**
   ```bash
   git branch
   ```
   *Digunakan untuk melihat daftar branch dan branch mana yang sedang aktif (ditandai dengan `*`).*

3. **Membuat file baru di branch `dev`**
   ```bash
   echo "Ini adalah konten dari branch dev" > file.txt
   ```
   *Perintah ini membuat file baru bernama `file.txt` dengan isi tertentu di branch `dev`.*

4. **Menambahkan file ke staging area**
   ```bash
   git add file.txt
   ```
   *Menambahkan file baru ke staging area agar siap di-commit.*

5. **Commit perubahan di branch `dev`**
   ```bash
   git commit -m "Menambahkan file.txt di branch dev"
   ```
   *Menyimpan snapshot perubahan ke repository lokal pada branch `dev`.*

6. **Kembali ke branch utama (`master`)**
   ```bash
   git checkout master
   ```
   *Berpindah ke branch utama. (Pada beberapa repo, nama branch utama bisa `main` atau `master`)*

7. **Merge branch `dev` ke `master`**
   ```bash
   git merge dev
   ```
   *Menggabungkan perubahan dari branch `dev` ke branch `master`.*

8. **Push perubahan ke repository remote**
   ```bash
   git push origin master
   ```
   *Mengirimkan commit dari branch `master` ke repository remote (GitHub).*

9. **Membuat tag versi (annotated tag)**
   ```bash
   git tag -a v1.0 -m "Rilis versi 1.0"
   ```
   *Membuat tag versi 1.0 dengan pesan rilis. Tag ini menandai commit tertentu sebagai versi rilis.*

10. **Push tag ke repository remote**
    ```bash
    git push origin v1.0
    ```
    *Mengirimkan tag `v1.0` ke repository remote agar bisa diakses di GitHub.*

---

Made by ***Dapuk***
