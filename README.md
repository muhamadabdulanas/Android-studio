# Android-studio

## Face Recognition

Untuk pengenalan wajah, Anda harus menggunakan gambar dengan dimensi minimal 480x360 piksel. Agar ML Kit dapat mendeteksi wajah secara akurat, gambar input harus berisi wajah yang direpresentasikan oleh data piksel yang memadai. Secara umum, setiap wajah yang ingin Anda deteksi dalam gambar harus berukuran minimal 100x100 piksel. Jika Anda ingin mendeteksi kontur wajah, ML Kit memerlukan input resolusi yang lebih tinggi: setiap wajah harus berukuran minimal 200x200 piksel.

Jika Anda mendeteksi wajah dalam aplikasi real-time, sebaiknya pertimbangkan juga dimensi keseluruhan gambar input. Gambar yang lebih kecil dapat diproses lebih cepat. Jadi, untuk mengurangi latensi, ambil gambar dengan resolusi lebih rendah. Namun, perhatikan persyaratan akurasi di atas dan pastikan wajah subjek menempati gambar sebanyak mungkin. Lihat juga tips untuk meningkatkan performa real-time.

Fokus gambar yang buruk juga dapat memengaruhi akurasi. Jika Anda tidak mendapatkan hasil yang dapat diterima, minta pengguna untuk mengambil ulang gambar.

Orientasi wajah terhadap arah kamera juga dapat memengaruhi fitur wajah yang terdeteksi oleh ML Kit. Baca Konsep Deteksi Wajah.

![image](https://github.com/muhamadabdulanas/pemrog-mobile13/assets/115569493/6a5838d0-6939-44f4-a426-99043b56f09b)
