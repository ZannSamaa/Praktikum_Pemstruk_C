# Modul Praktikum - Minggu 01 - Pengantar
**Henokh Lugo Hariyanto**

## Tujuan
- Mampu menjalankan program JavaScript di browser maupun di Node.js.
- Mampu menuliskan laporan sederhana menggunakan Markdown.

---

## Deskripsi Praktikum

Pada modul praktikum ini, kita mempelajari cara menjalankan program JavaScript sederhana melalui Web Browser, melakukan instalasi VSCode, instalasi Node.js, serta menjalankan kode JavaScript menggunakan Node.js.

Tips dalam mempelajari bahasa pemrograman adalah dengan mengetik ulang setiap perintah yang ditemukan, kemudian mengubah-ubahnya untuk menguji pemahaman. Proses eksplorasi sangat penting agar benar-benar memahami cara kerja setiap perintah.

---

# Menjalankan Kode JavaScript di Web Browser

## 1. Membuat Direktori

Buat sebuah folder dengan nama:

```
hello
```

Folder ini akan digunakan untuk menyimpan file JavaScript dan file HTML.

---

## 2. Membuat File JavaScript

Di dalam folder `hello`, buat file dengan nama:

```
hello.js
```

Isi file `hello.js` dengan kode berikut:

```javascript
console.log("Halo Dunia");
alert("Halo Dunia");
```

Penjelasan:
- `console.log()` digunakan untuk menampilkan pesan pada Console browser.
- `alert()` digunakan untuk menampilkan pesan dalam bentuk popup.

---

## 3. Membuat File HTML

Selanjutnya, buat file HTML dengan nama:

```
hello.html
```

Isi file tersebut dengan kode berikut:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Belajar JavaScript</title>
</head>
<body>

<h1>Belajar JavaScript Pertama</h1>

<script src="hello.js"></script>

</body>
</html>
```

Penjelasan:
Tag `<script src="hello.js"></script>` digunakan untuk menghubungkan file JavaScript ke dalam file HTML agar dapat dijalankan oleh browser.

---

## 4. Menjalankan Program

Langkah menjalankan program:

1. Buka browser (misalnya Google Chrome).
2. Tekan `Ctrl + O`.
3. Pilih file `hello.html`.
4. Klik Open.

Jika berhasil:
- Akan muncul popup bertuliskan "Halo Dunia".
- Console browser akan menampilkan teks "Halo Dunia".
- Halaman akan menampilkan tulisan "Belajar JavaScript Pertama".

Untuk melihat Console:
- Tekan `F12`
- Pilih tab **Console**

---

# Instalasi Visual Studio Code (VSCode)

Terdapat banyak tutorial di internet maupun YouTube mengenai cara instalasi Visual Studio Code (VSCode) pada sistem operasi Windows, Mac, maupun Linux. Pada bagian ini dijelaskan secara singkat langkah-langkah instalasi VSCode.

---

## 1. Mengunduh Installer VSCode

Buka tautan resmi berikut melalui browser:

https://code.visualstudio.com/download

Kemudian pilih installer sesuai dengan sistem operasi yang digunakan:
- Windows
- Mac
- Linux

Unduh berkas installer tersebut.

---

## 2. Menjalankan Installer

Setelah proses unduhan selesai:

1. Jalankan berkas installer yang telah diunduh.
2. Ikuti langkah-langkah yang ditampilkan pada dialog instalasi.
3. Gunakan pengaturan default jika tidak ada kebutuhan khusus.
4. Tunggu hingga proses instalasi selesai.

Jika instalasi berhasil, maka akan muncul tampilan **Welcome Page** saat VSCode dibuka.

---

## 3. Menentukan Working Directory

Setelah VSCode terpasang, langkah berikutnya adalah menentukan **working directory** atau folder kerja untuk menyimpan seluruh berkas kode JavaScript selama praktikum.

Disarankan untuk membuat satu folder utama, misalnya:

```
praktikum-javascript
```

Di dalam folder tersebut, buat subfolder untuk setiap pertemuan agar lebih terstruktur, contohnya:

```
praktikum-javascript/
│
├── week-01/
├── week-02/
├── week-03/
```

Dengan struktur seperti ini, berkas-berkas praktikum akan lebih tertata rapi dan mudah dikelola.

---

## Kesimpulan

Instalasi VSCode dilakukan dengan mengunduh installer dari situs resmi, menjalankan proses instalasi sesuai petunjuk, dan menentukan working directory yang terstruktur untuk menyimpan seluruh berkas praktikum. Struktur folder yang rapi akan membantu dalam pengelolaan kode selama proses pembelajaran.