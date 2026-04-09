# 📄 Test Scenario - Login Feature

## 📌 Application

SauceDemo
URL: https://www.saucedemo.com/

---

## 🧩 Module

Authentication - Login Form

---

## 🎯 Objective

Menyusun skenario pengujian untuk memastikan fitur login dapat menangani berbagai kondisi input dan perilaku user secara benar.

---

## 📋 Test Scenarios

### ✅ Positive Scenarios

1. User login dengan username dan password valid (standard_user)
2. User login dengan user yang memiliki karakteristik khusus namun valid (problem_user)

---

### ❌ Negative Scenarios

3. User login dengan username tidak terdaftar
4. User login dengan password salah
5. User login dengan username kosong
6. User login dengan password kosong
7. User login dengan kedua field kosong
8. User login dengan user terkunci (locked_out_user)

---

### ⚠️ Boundary Scenarios

9. User login dengan username sangat panjang
10. User login dengan password sangat panjang
11. User login dengan password di bawah batas minimum karakter

---

### ⚡ Performance Scenario

12. User login menggunakan performance_glitch_user untuk menguji delay/performa sistem

---

### 🐞 Error Handling Scenario

13. User login menggunakan error_user untuk memicu error tertentu pada sistem

---

### 🎨 UI / Visual Scenario

14. User login menggunakan visual_user untuk mengidentifikasi potensi issue pada tampilan UI

---

### 🔐 Security Scenarios

15. User mencoba login menggunakan SQL Injection pada field username
16. User mencoba login menggunakan script injection (XSS)

---

## 🚀 Expected Result

* Sistem menerima login dengan credential valid
* Sistem menolak login dengan credential tidak valid
* Sistem menampilkan error message yang sesuai
* Sistem tetap stabil pada kondisi ekstrem dan input tidak valid
