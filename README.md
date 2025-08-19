# Proyek Sederhana: ViewModel dan LiveData

Aplikasi ini adalah contoh dasar penggunaan `ViewModel` dan `LiveData` dari Android Jetpack. Tujuannya adalah untuk menunjukkan cara mempertahankan data sederhana saat terjadi perubahan konfigurasi, seperti rotasi layar.

## 🎯 Fitur Utama

* Aplikasi ini hanya terdiri dari satu halaman yang menampilkan sebuah angka (counter).
* Terdapat sebuah tombol untuk menaikkan angka tersebut.
* Angka pada penghitung **tidak akan hilang (reset)** meskipun layar diputar, karena datanya disimpan di dalam `ViewModel`.

## 🛠️ Teknologi yang Digunakan

* **Bahasa**: Kotlin
* **Komponen**: Android Jetpack (`ViewModel`, `LiveData`)

## 🚀 Cara Mencoba

1.  Buka dan jalankan proyek ini di **Android Studio**.
2.  Tekan tombol "Tambah" beberapa kali untuk mengubah angka.
3.  **Putar layar perangkat** Anda (dari portrait ke landscape atau sebaliknya).
4.  Lihat bagaimana angka yang ditampilkan tetap sama dan tidak kembali ke nol.
   
## Hasil Tampilan:
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/372135a2-5b43-499a-a548-6dc5fdcbbc3b" width="300"/>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/c0afd367-f467-49f7-a94c-1569142d6dee" width="300"/>
    </td>
  </tr>
</table>
