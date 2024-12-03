# JOBSHEET 12 (PRAKTIKUM 7)

Nama: Wulan Maulidya P. F

Kelas: TI-3H

No. Absen: 27

NIM: 2241720174

---

## PRAKTIKUM 7

### Langkah 1: Buat Project Baru

Buatlah sebuah project flutter baru dengan nama bloc_random_nama (beri nama panggilan Anda) di folder week-12/src/ repository GitHub Anda. Lalu buat file baru di folder lib dengan nama random_bloc.dart

### Langkah 2: Isi kode random_bloc.dart
Ketik kode impor berikut ini.

![Praktikum](/images/p7_l2.png)

### Langkah 3: Buat class RandomNumberBloc()

![Praktikum](/images/p7_l3.png)

### Langkah 4: Buat variabel StreamController
Di dalam class RandomNumberBloc() ketik variabel berikut ini

![Praktikum](/images/p7_l4.png)

### Langkah 5: Buat constructor

![Praktikum](/images/p7_l5.png)

### Langkah 6: Buat method dispose()

![Praktikum](/images/p7_l6.png)

### Langkah 7: Edit main.dart

![Praktikum](/images/p7_l7.png)

### Langkah 8: Buat file baru random_screen.dart
Di dalam folder lib project Anda, buatlah file baru ini.

### Langkah 9: Lakukan impor material dan random_bloc.dart
Ketik kode ini di file baru random_screen.dart

![Praktikum](/images/p7_l9.png)

### Langkah 10: Buat StatefulWidget RandomScreen
Buatlah di dalam file random_screen.dart

![Praktikum](/images/p7_l10.png)

### Langkah 11: Buat variabel
Ketik kode ini di dalam class _RandomScreenState

![Praktikum](/images/p7_l11.png)

### Langkah 12: Buat method dispose()
Ketik kode ini di dalam class _StreamHomePageState

![Praktikum](/images/p7_l12.png)

### Langkah 13: Edit method build()
Ketik kode ini di dalam class _StreamHomePageState

![Praktikum](/images/p7_l13.png)

Run aplikasi, maka Anda akan melihat angka acak antara angka 0 sampai 9 setiap kali menekan tombol FloactingActionButton.

![Praktikum](/images/p7_l13.gif)

**Soal 13** Jelaskan maksud praktikum ini ! Dimanakah letak konsep pola BLoC-nya ?

* Praktikum ini menunjukkan penerapan pola BLoC untuk memisahkan logika bisnis dari tampilan dalam aplikasi Flutter. Dengan menggunakan stream dan controller untuk mengelola input dan output, aplikasi ini menjadi lebih terstruktur dan mudah dipelihara. Pola BLoC memungkinkan pengembangan aplikasi yang lebih baik dengan membuat kode lebih modular dan terpisah, serta meningkatkan kemampuan pengujian dan pemeliharaan.