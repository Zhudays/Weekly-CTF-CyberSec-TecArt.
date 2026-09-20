# Write-Up CTF & Dokumentasi Environment Setup

## 1. Profil Peserta
* Nama: Ngurah Gde Wisnu Kertha Murthi
* NIM: 260530411111
* Program Studi: Teknik Elektro

## 2. Kategori CTF
* Kategori: Forensics
* Nama Challenge: Information

## 3. Tools yang Diinstalasi
1. Burp Suite
2. Ghidra
3. CodeBrowser

## 4. Dokumentasi Proses Instalasi & Pengujian Tools
<img width="1920" height="1080" alt="ce84bfd3-a2c0-4444-b5d3-7b930ce1144c" src="https://github.com/user-attachments/assets/15cfaec7-b98e-4816-a1f9-a1795992e550" />
<img width="1920" height="1080" alt="4b53ffb6-b183-4662-8aa1-531722e3e5e2" src="https://github.com/user-attachments/assets/52a49d82-00f0-47dd-9062-cad1c1b1e523" />
                                                           
### A. Instalasi
Burp Suite, Ghidra, CodeBrowser: saya menginstal software tools via terminal

## 5. Langkah-Langkah Penyelesaian Challenge

### A. Deskripsi Challenge
Challange Undo
2. saya ke terminal dan mengakses python
3. waktu saya masukan instance, ada petunjuk base64 reverse,lalu saya memasukkan command untuk bisa dapet ke flag selanjutnya
4. lalu saya dapet lanjut ke flag selanjutnya, saya coba command tr, beberapa kali saya coba hingga saya berhasil capture flag terakhir dan berhasil solve challange undonya

Challange Information
1. Saya mengakses file cat.jpg via exiftool di terminal
2. Lalu saya buka direktori downloads untuk mengakses file cat.jpg untuk dicheck metadatanya
3. Ketemu lisensenya dan saya decode base64 dan ketemu flagnya

Challange Icibos Tecart 0
1. Saya mengakses file cat.jpg via exiftool di terminal
2. Lalu saya buka direktori downloads untuk mengakses file cat.jpg untuk dicheck metadatanya
3. Ketemu lisensenya dan saya decode base64 dan ketemu flagnya

Challange Icibos Tecart 1
1. Saya ngebuka file program1 di CodeBrowser, dan menemukan flag palsu
2. Saya mencoba menjalankan program di terminal dan ada diminta untuk memasukkan kata ajaib, saya mencoba banyak kalimat yang saya temukan di code Browser
3. Setelah sekian percobaan, saya menemukan kata ajaib dan berhasil capture the flag

<img width="1600" height="900" alt="WhatsApp Image 2026-09-10 at 11 06 22 AM" src="https://github.com/user-attachments/assets/08519095-37c8-4087-bc61-3c8b5b9d2411" />
<img width="1536" height="864" alt="image" src="https://github.com/user-attachments/assets/7461c76d-c284-4a90-9888-5eeedda091fd" />
