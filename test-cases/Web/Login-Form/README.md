# 🔐 Login Form Testing

## 📌 Deskripsi

Module ini berisi dokumentasi **manual testing** untuk fitur **Login Form** pada aplikasi web SauceDemo.

Pengujian dilakukan untuk memastikan proses autentikasi berjalan dengan benar serta mampu menangani berbagai kondisi input dari pengguna.

---

## 🎯 Tujuan Pengujian

* Memvalidasi proses login dengan credential yang benar
* Memastikan sistem menolak credential yang tidak valid
* Menguji validasi input pada field username dan password
* Mengidentifikasi bug atau error pada fitur login

---

## 🔍 Ruang Lingkup (Scope)

* Input username
* Input password
* Validasi error message
* Behavior sistem setelah login (success / failed)

---

## 🧪 Jenis Pengujian

* Functional Testing
* Negative Testing
* Boundary Testing
* Basic Security Testing

---

## 📂 Struktur Module

```bash id="n5jdxu"
login-form/
├── test-suite-login.md
├── test-scenario.md
├── test-case.md
├── bug-report.md
└── evidence/
```

---

## 🗂 Artefak Pengujian

| Dokumen       | Deskripsi                                      |
| ------------- | ---------------------------------------------- |
| Test Suite    | Strategi dan ruang lingkup pengujian           |
| Test Scenario | Daftar skenario pengujian                      |
| Test Case     | Detail langkah pengujian dalam format Markdown |
| Bug Report    | Dokumentasi bug yang ditemukan                 |
| Evidence      | Screenshot hasil pengujian                     |

---

## 🌐 Lingkungan Pengujian

* Website: https://www.saucedemo.com/
* Browser: Google Chrome
* Platform: Web Application
* Metode: Manual Testing

---

## 🔐 Test Data

| Username        | Password     | Keterangan         |
| --------------- | ------------ | ------------------ |
| standard_user   | secret_sauce | Valid user         |
| locked_out_user | secret_sauce | User terkunci      |
| invalid_user    | wrong_pass   | Invalid credential |

---

## 🚀 Expected Outcome

* User berhasil login dengan credential valid
* Sistem menampilkan error message yang sesuai untuk input tidak valid
* Sistem tetap stabil terhadap input ekstrem atau tidak valid

---

## 📌 Catatan

Module ini dirancang sebagai simulasi pengujian fitur login di dunia nyata dengan pendekatan yang terstruktur dan mengikuti praktik **Quality Assurance (QA)** di industri.

---

> Pengujian akan terus diperbarui dengan penambahan test case dan peningkatan kualitas dokumentasi.
