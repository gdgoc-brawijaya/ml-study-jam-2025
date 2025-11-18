# 📜 Git Cheatsheet: Panduan "First Commit" Kalian

Bingung cara upload tugas ke GitHub? Ikuti alur ini!

---

## 1️⃣ Membuat Repositori (Di Website GitHub)

1.  Buka [GitHub.com](https://github.com) dan login.
2.  Klik tombol **New** (hijau) atau tanda **+** di pojok kanan atas.
3.  **Repository name:** Isi nama bebas (misal: `my-ml-journey`).
4.  **Public/Private:** Pilih sesuai selera.
5.  **Initialize this repository with:** Centang **Add a README file**.
6.  Klik **Create repository**.

---

## 2️⃣ Menghubungkan ke Laptop (Clone)

1.  Di halaman repo yang baru dibuat, klik tombol hijau **Code**.
2.  Copy link HTTPS-nya (contoh: `https://github.com/username/my-ml-journey.git`).
3.  Buka Terminal / Git Bash di laptop (atau Terminal di VS Code).
4.  Pindah ke folder tempat kamu ingin menyimpan proyek, lalu ketik:
    ```bash
    git clone <PASTE_LINK_TADI_DISINI>
    ```
5.  Masuk ke folder yang baru muncul:
    ```bash
    cd my-ml-journey
    ```

---

## 3️⃣ Melakukan Perubahan (Edit)

1.  Buka folder tersebut di **VS Code**.
2.  Edit file `README.md` sesuai tugas Chapter 1 (Nama, Interest, Harapan).
3.  Save file (`Ctrl+S` / `Cmd+S`).

---

## 4️⃣ Menyimpan & Upload (The Holy Trinity)

Setiap kali selesai mengedit, jalankan 3 perintah suci ini di terminal VS Code:

### a. Add (Pilih file)

Memberitahu Git file mana yang mau disimpan. Tanda titik `.` artinya "semua file".

```bash
git add .
```

### b. Commit (Bungkus file)

Membungkus perubahan dengan pesan catatan.

```bash
git commit -m "Menambahkan profil dan harapan saya"
```

### c. Push (Kirim ke GitHub)

Mengirim bungkusan tadi ke website GitHub.

```bash
git push
```

---

## 🎉 Selesai!

Cek kembali halaman GitHub kalian di browser, refresh. Tulisan kalian seharusnya sudah muncul di sana!

---

### 🆘 Error Umum

**Error:** _Authentication failed / Please enter username..._
**Solusi:** Masukkan username dan password GitHub kalian.
_Note: Jika password gagal, kalian mungkin perlu membuat "Personal Access Token" di GitHub Settings > Developer Settings._

**Error:** _Please tell me who you are._
**Solusi:** Kamu belum setting nama/email. Jalankan:

```bash
git config --global user.name "Nama Kamu"
git config --global user.email "email@kamu.com"
```
