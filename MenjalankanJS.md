# Menjalankan Kode JavaScript di Node.js

Setelah proses instalasi Visual Studio Code (VSCode) dan Node.js berhasil dilakukan, proses pembelajaran JavaScript dapat dilakukan dengan lebih mudah dan terstruktur.

---

## 1. Membuka Working Directory di VSCode

1. Buka VSCode.
2. Klik menu **File** → **Open Folder**.
3. Pilih direktori praktikum yang telah dibuat sebelumnya (misalnya `praktikum-javascript/week-01`).
4. Klik **Select Folder**.

---

## 2. Membuat Berkas JavaScript

Buat file baru dengan ekstensi `.js`, misalnya:

```
app.js
```

Contoh isi kode JavaScript:

```javascript
console.log("Halo dari Node.js");
```

Simpan berkas tersebut.

---

## 3. Membuka Terminal di VSCode

Jika terminal belum terlihat:

1. Klik menu **Terminal**
2. Pilih **New Terminal**

Terminal akan muncul di bagian bawah VSCode.

---

## 4. Menjalankan Kode JavaScript

Pastikan posisi direktori pada terminal sudah berada di folder tempat file `app.js` berada.

Jika belum, arahkan direktori menggunakan perintah:

```bash
cd nama-folder
```

Untuk menjalankan file JavaScript, ketik perintah berikut:

```bash
node app.js
```

---

## 5. Hasil yang Diharapkan

Jika berhasil, maka akan muncul output berikut pada terminal:

```
Halo dari Node.js
```

---

## Kesimpulan

Node.js memungkinkan kita menjalankan kode JavaScript di luar browser, langsung melalui terminal. Dengan menggunakan VSCode dan Node.js, proses pengembangan dan pengujian program JavaScript menjadi lebih fleksibel dan efisien.