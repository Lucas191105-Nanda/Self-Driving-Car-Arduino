# 🚗 Self Driving Car with Arduino (Autonomous Car Project)

Project ini adalah **mobil self-driving sederhana** berbasis **Arduino**, menggunakan sensor ultrasonic untuk mendeteksi jarak, motor DC untuk pergerakan, serta sistem kontrol otomatis untuk menghindari rintangan.

Project ini dibuat sebagai tugas sekolah / proyek pribadi untuk mempelajari dasar **embedded system**, **sensor detection**, dan **otomasi robotik**.

---

## ⚙️ Teknologi & Komponen yang Digunakan

### 🔌 Hardware
- Arduino UNO / Arduino Nano
- Sensor Ultrasonic HC-SR04 (untuk deteksi jarak)
- Motor Driver L298N / L293D
- 2× Motor DC (rangkaian roda kanan & kiri)
- Chassis / Base Car
- Baterai Lithium ion
- Jumper Wires

### 💻 Software
- Arduino IDE
- Library NewPing (opsional)
- C/C++ (Arduino)

---

## 🧠 Cara Kerja Sistem (Overview)

Mobil akan bergerak maju secara otomatis.  
Jika sensor ultrasonic mendeteksi objek pada jarak tertentu, Arduino akan:

1. **Menghentikan motor**
2. Mengukur jarak kiri dan kanan
3. Memilih arah terbaik (yang lebih luas / tidak ada halangan)
4. **Belok ke arah aman**
5. Melanjutkan perjalanan

---

## 📸 Screenshot / Dokumentasi

> Upload gambar di GitHub, lalu masukkan seperti contoh di bawah:

![Car Front View](/images/screenshot1.jpg)

> **Cara menambahkan screenshot:**  
> 1. Buat folder `images` di repo kamu  
> 2. Upload gambar lewat drag & drop  
> 3. Gunakan format:  
> ```
> ![Alt Text](images/nama_file.jpg)
> ```

---

## 🛠 Cara Instalasi & Upload Program

1. Download atau clone repository:
   ```bash
   git clone https://github.com/username/self-driving-car.git
  Buka file .ino di Arduino IDE.

2. Pilih board:
Tools → Board → Arduino Uno / Nano

3. Pilih port:
Tools → Port

4. Upload program:
Klik Upload (Ctrl + U)
