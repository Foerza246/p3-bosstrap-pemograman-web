# pertanyaan

### 1. jelaskan keputusan grid-cols/gap di tiap breakpoint — kenapa begitu?
- Mobile: agar tetap mudah dibaca di layar kecil dan gap juga dibuat kecil 
- Tablet: agar bisa untuk memberi ruang antar elemen
- Desktop: supaya tampilan terasa lega di layar besar

---

### 2. Bagaimana kamu memanfaatkan tility responsive Tailwind untuk memecahkan masalah layout yang muncul di mobile?
Saya memanfaatkan layout default fokus ke layar kecil. Misalnya **grid-cols-1** supaya elemen tampil vertikal, dan **gap-2** biar tetap ada jarak tapi tidak boros tempat

---

### 3. jelaskan trade-off antara memakai banyak utility classes vs membuat component CSS tersendiri.
- utility classes : bikin proses styling lebih cepat dan juga menjadi konsisten. tapi bikin html jadi penuh class
- component css : lebih bikin rapi, jadinya harus butuh lebih banyak waktu untuk estrak css
