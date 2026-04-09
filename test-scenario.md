# Test Scenario - Login Feature

## Application
SauceDemo (https://www.saucedemo.com/)

## Module
Authentication - Login

---

## ✅ Positive Scenario

1. User login dengan username dan password valid

---

## ❌ Negative Scenario

2. User login dengan password salah  
3. User login dengan username tidak terdaftar  
4. User login dengan username kosong  
5. User login dengan password kosong  
6. User login dengan kedua field kosong  
7. User login dengan format username tidak valid  

---

## ⚠️ Boundary Scenario

8. User login dengan username sangat panjang  
9. User login dengan password di bawah minimum karakter  
10. User login dengan password sangat panjang  

---

## 🔐 Security Scenario

11. User mencoba login dengan SQL Injection pada field username  
12. User mencoba login dengan script injection (XSS)  

---

## 🎯 Expected Result

- Sistem hanya mengizinkan login dengan credential valid  
- Sistem menampilkan error message yang sesuai untuk input tidak valid  
- Sistem tetap stabil dan tidak crash terhadap input ekstrem atau berbahaya  
