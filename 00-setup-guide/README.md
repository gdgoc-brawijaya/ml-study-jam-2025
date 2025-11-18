# 🛠️ Setup Guide: Menyiapkan "Bengkel" Machine Learning

Selamat datang di **Chapter 0**!

Sebelum kita belajar cara berpikir seperti seorang ML Engineer, kita harus menyiapkan alat tempurnya dulu. Di dunia profesional, kita tidak selamanya bisa bergantung pada _cloud_ (seperti Google Colab). Kita harus bisa membangun _environment_ di laptop sendiri (Local Environment).

Ikuti langkah-langkah di bawah ini dengan teliti. **Jangan dilewatkan satu pun!**

---

## 📋 Checklist Instalasi

1. [ ] **Python** (Mesin utamanya)
2. [ ] **Git** (Alat penyimpan & portofolio)
3. [ ] **Visual Studio Code** (Tempat kita bekerja)
4. [ ] **Punya Akun GitHub** (Daftar di [github.com](https://github.com) jika belum punya)

---

## 1️⃣ Langkah 1: Install Python (The Engine)

Python adalah bahasa pemrograman yang akan kita gunakan.

1.  Kunjungi website resmi: [**Download Python**](https://www.python.org/downloads/)
2.  Download versi terbaru (rekomendasi: **3.10** atau **3.11**).
3.  **⚠️ PENTING (KHUSUS WINDOWS):**
    Saat installer terbuka, **WAJIB CENTANG** kotak bertuliskan:

    > **[v] Add Python.exe to PATH**

    _(Jika ini lupa dicentang, perintah python tidak akan dikenali di terminal!)_

4.  Lanjutkan instalasi dengan klik **"Install Now"** sampai selesai.

### ✅ Cek Instalasi Python

Buka Terminal (Mac/Linux) atau CMD/PowerShell (Windows), lalu ketik:

```bash
python --version
# Atau jika error, coba: python3 --version
```

Jika muncul angka versi (misal `Python 3.11.5`), berarti **SUKSES**.

---

## 2️⃣ Langkah 2: Install Git (The Version Control)

Git akan kita gunakan untuk meng-upload tugas dan proyek kalian ke GitHub.

1.  Kunjungi link ini: [**Download Git**](https://git-scm.com/downloads)
2.  Download sesuai sistem operasi kalian.
3.  Lakukan instalasi (klik Next, Next, Next saja sampai selesai, pengaturan default sudah cukup bagus).

### ✅ Cek Instalasi Git

Di terminal/CMD, ketik:

```bash
git --version
```

Jika muncul versi git (misal `git version 2.41.0`), berarti **SUKSES**.

### ⚙️ Konfigurasi Wajib Git (PENTING!)

Agar Git tahu siapa kamu saat menyimpan file, kamu wajib mendaftarkan nama dan email.
Jalankan 2 perintah ini di terminal (ganti dengan nama & email kamu):

```bash
git config --global user.name "Nama Lengkap Kamu"
git config --global user.email "emailmu@contoh.com"
```

**Cek apakah sudah berhasil:**

```bash
git config --list
```

Jika nama dan emailmu muncul di daftar, berarti aman!

---

## 3️⃣ Langkah 3: Install VS Code (The Editor)

Kita butuh editor yang nyaman dan canggih. VS Code adalah standar industri saat ini.

1.  Download di sini: [**Download Visual Studio Code**](https://code.visualstudio.com/)
2.  Install seperti biasa.
3.  **Install Extensions Wajib:**
    Setelah VS Code terbuka:
    - Klik ikon kotak-kotak di menu kiri (**Extensions**).
    - Cari dan Install: **Python** (by Microsoft).
    - Cari dan Install: **Jupyter** (by Microsoft).

---

## 4️⃣ Langkah 4: The "Final Check" (Wajib!)

Mari kita pastikan semuanya bekerja bersamaan dengan menjalankan kode Python pertama kalian di Jupyter Notebook.

1.  Buka **VS Code**.
2.  Buat file baru: `File` > `New File...`
3.  Simpan file dengan nama: **`test_setup.ipynb`** (Pastikan akhiran file-nya `.ipynb`, bukan `.py`).
4.  Ketik kode berikut di dalam kotak (cell) pertama:
    ```python
    print("Halo GDGoC! Setup saya sudah berhasil! 🚀")
    ```
5.  Klik tombol **Play (▶️)** di samping kiri cell tersebut.
    - _💡 Tip: Jika terminal bawah tidak muncul, tekan tombol `Ctrl` + `J` (Windows/Linux) atau `Cmd` + `J` (Mac)._
    - _Note:_ Jika diminta memilih "Kernel", pilih **Python 3.x.x** yang tadi baru diinstall.
6.  Jika muncul tulisan output di bawahnya, selamat! **Laptop kamu resmi siap untuk Chapter 1!**

---

## ❓ Troubleshooting (Masalah Umum)

**Q: Saat ketik `python --version`, muncul tulisan "not recognized" atau error.**
A: Kemungkinan besar kamu lupa mencentang **"Add to PATH"** saat install Python.

- _Solusi:_ Uninstall Python, lalu Install ulang. Jangan lupa centang kotaknya kali ini!

**Q: VS Code tidak bisa menjalankan file `.ipynb`.**
A: Pastikan Extension **Jupyter** dan **Python** sudah terinstall dan statusnya "Enabled". Coba restart VS Code.

**Q: Masih error?**
A: Catat pesan error-nya, screenshot, dan tanyakan di grup atau bawa saat sesi berlangsung!

---

**See you at Chapter 1!** 👋
