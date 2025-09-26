# pertanyaan

### 1. Mengapa memilih konfigurasi (**col-**) tertentu untuk tiap breakpoint?
Saya pilih **col-12 di mobile**, **col-md-6 di tablet**, dan **col-lg-3 di desktop** agar tata letak selalu nyaman di setiap device.  
- Mobile: 1 kolom penuh biar gambar ga terlalu kecil
- Tablet: 2–3 kolom seimbang antara ukuran gambar dan jumlah yang tampil
- Desktop: 4 kolom lebih rapat dan mirip layout Instagram asli

---

### 2. Bagaimana memastikan tombol *Follow / Edit Profile* tetap mudah dijangkau di mobile?
Saya gunakan kombinasi antara (flex-column) di mobile dan (flex-row) di desktop  
Ditambah dengan (**kelas order-**), tombol agar bisa saling bertukar posisi dengan sesuai kebutuhan layar.  
Hasilnya:  
- Mobile: tombol ini ditumpuk (vertical), biar mudah ditekan dengan jempol  
- Desktop: tombol berjajar di kanan, pasti lebih estetik dan rapi

---

### 3. Jika postingan bertambah jadi 50, apa potensi masalah dan bagaimana solusi grid mengatasinya?
Potensi masalah: halaman jadi terlalu panjang, jadinya pengguna  harus banyak scroll.  
Solusi:  
- Grid tetap aman, karena Bootstrap akan otomatis melanjutkan baris ke bawah
- Untuk efisiensi, jadi bisa tambahkan **pagination** atau **lazy loading** (misalnya load 12 gambar dulu, sisanya saat scroll)
- jadinya performa tetap terjaga dan pengguna tidak merasa berat saat membuka halaman