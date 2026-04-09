# 🧪 Test Suite - Login Feature

## 📌 Application

SauceDemo
URL: https://www.saucedemo.com/

---

## 🧩 Module

Authentication - Login Form

---

## 🎯 Objective

Memastikan fitur login berfungsi dengan benar dalam berbagai kondisi, termasuk input valid, tidak valid, serta kondisi khusus yang dapat mempengaruhi performa dan stabilitas sistem.

---

## 🔍 Scope of Testing

Pengujian difokuskan pada:

* Validasi input username dan password
* Proses autentikasi user
* Penanganan error message
* Perilaku sistem setelah login (success / failure)
* Respons sistem terhadap berbagai tipe user

---

## 🚫 Out of Scope

* Pengujian database secara langsung
* Pengujian API backend secara detail
* Pengujian keamanan tingkat lanjut (penetration testing)

---

## 🧪 Test Types

* Functional Testing
* Negative Testing
* Boundary Testing
* Basic Security Testing

---

## ⚙️ Test Environment

* Platform: Web Application
* Browser: Google Chrome
* OS: Windows 10

---

## 🔐 Test Data

| Username                | Password     | Keterangan                         |
| ----------------------- | ------------ | ---------------------------------- |
| standard_user           | secret_sauce | User normal (valid login)          |
| locked_out_user         | secret_sauce | User terkunci (tidak dapat login)  |
| problem_user            | secret_sauce | User dengan potensi issue aplikasi |
| performance_glitch_user | secret_sauce | User dengan performa lambat        |
| error_user              | secret_sauce | User yang memicu error tertentu    |
| visual_user             | secret_sauce | User dengan kemungkinan issue UI   |

---

## 📋 Entry Criteria

* Aplikasi dapat diakses melalui browser
* Halaman login berhasil dimuat
* Test data tersedia dan valid

---

## ✅ Exit Criteria

* Seluruh test case telah dieksekusi
* Bug yang ditemukan telah didokumentasikan
* Tidak ada bug dengan severity High yang belum dicatat

---

## 📊 Test Deliverables

* Test Scenario
* Test Case
* Bug Report
* Evidence (Screenshot)

---

## ⚠️ Risks & Assumptions

### Risks

* Koneksi internet tidak stabil dapat mempengaruhi hasil testing
* Performa aplikasi dapat berbeda tergantung kondisi server

### Assumptions

* Sistem backend berjalan dengan normal
* Test data tetap konsisten selama pengujian

---

## 🚀 Expected Outcome

* Sistem hanya mengizinkan login dengan credential valid
* Sistem menolak akses untuk user yang tidak valid atau terkunci
* Sistem memberikan feedback (error message) yang sesuai
* Sistem tetap stabil dalam berbagai kondisi input
