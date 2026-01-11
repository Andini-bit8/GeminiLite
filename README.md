# GeminiLite
Aplikasi mobile Android berbasis Kotlin yang mereplikasi fitur dasar media sosia
## 👤 Identitas Pengembang
* **Nama:** Nisra Padila
* **NIM:** 2304411070
* **Nama:** Sri wahyuni
* **NIM:** 2304411550
* **Kelas:** 5K RPL 3
* **Prodi:** Informatika - Universitas Cokroaminoto Palopo

# GeminiLite 🤖✨

**GeminiLite** adalah aplikasi asisten cerdas berbasis Android yang dirancang sebagai tugas ujian pengembangan aplikasi mobile. Aplikasi ini terinspirasi dari **Google Gemini**, memungkinkan pengguna untuk berinteraksi, mengelola percakapan (prompt), dan mendapatkan informasi secara real-time melalui antarmuka yang modern.

---

## 📝 Deskripsi Proyek
GeminiLite menghadirkan pengalaman asisten digital di mana pengguna dapat mengirimkan pesan/prompt, melihat riwayat interaksi, mencari topik tertentu, serta mengelola data percakapan mereka sendiri hapus).

* **Aplikasi Rujukan:** [Google Gemini di Play Store](https://play.google.com/store/apps/details?id=com.google.android.apps.bard)
* **Arsitektur:** Model-View-Controller (MVC)
* **Bahasa:** Kotlin

---

## 🛠️ Stack Teknologi
* **IDE:** Android Studio (Ladybug/Koala)
* **Backend:** Firebase (Authentication & Realtime Database)
* **UI Component:** Material Design 3, RecyclerView, Fragments

---

## ✅ Fitur & Kriteria Ujian
Aplikasi ini telah memenuhi seluruh poin penilaian teknis:

### 🔐 Firebase Authentication
* **Multi-Method Login:** Keamanan akses menggunakan akun Email/Password dan integrasi **Google Sign-In**.

### 🔄 Realtime CRUD (Firebase Database)
* **Create:** Mengirimkan prompt atau pesan baru ke asisten.
* **Read:** Menampilkan riwayat percakapan secara real-time di halaman utama.
* **Delete:** Menghapus riwayat percakapan tertentu dari database.

### 🏗️ Implementasi Komponen Android
* **Fragment:** Implementasi untuk mencari riwayat percakapan atau topik.
* **Intent:** Navigasi antar Activity (Splash Screen -> Login -> Dashboard).
* **RecyclerView:** Menampilkan daftar chat/pesan dengan performa yang ringan dan responsif.
* **Notification:** Munculnya notifikasi lokal sebagai konfirmasi saat data berhasil diproses atau dikirim.

---

## 👨‍💻 Developer
* **GitHub:** [Andini-bit8](https://github.com/Andini-bit8)
* ![Image](https://github.com/user-attachments/assets/ad3403ca-cb44-4d0f-ba7c-2216b7acf455)

![Image](https://github.com/user-attachments/assets/dd5bb304-92ef-4f02-bd6f-e1467e4373fa)
![Image](https://github.com/user-attachments/assets/68e0c73e-3b15-48ae-9aa0-52ebbbcaef71)
![Image](https://github.com/user-attachments/assets/aea9268f-b6fb-41ee-9c3c-cb2639499f4d)
* 









🚀 Cara Menjalankan Aplikasi
Clone repository ini:
git clone https://github.com/Andini-bit8/GeminiLite
Buka project menggunakan Android Studio.
Pastikan file google-services.json sudah terhubung dengan akun Firebase Anda (atau gunakan file yang sudah disertakan jika public).
Tunggu proses Gradle Sync selesai.
Jalankan aplikasi (Run 'app') pada Emulator atau Perangkat Fisik.

