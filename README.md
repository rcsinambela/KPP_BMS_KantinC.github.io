# KPP_BMS_KantinC.github.io
**Pastikan Anda sudah diundang terlebih dahulu**

Untuk dapat bergabung ke sebuah proyek dan dapat melakukan pull dan push dari lokal/repo, Anda perlu mengikuti beberapa langkah umum dalam pengelolaan proyek kolaboratif menggunakan sistem kontrol versi seperti Git. Berikut adalah panduan umumnya:

1. **Clone Repo:**
   - Setiap anggota tim harus melakukan "cloning" repo proyek ke lokal masing-masing dengan menggunakan perintah `git clone`. Contohnya:
     ```
     git clone <URL_REPO>
     ```

2. **Buat Cabang (Branch) Baru:**
   - Setiap anggota tim sebaiknya membuat cabang baru untuk bekerja pada fitur atau perbaikan tertentu. Ini membantu dalam mengisolasi perubahan dan menghindari konflik. Gunakan perintah `git checkout -b` untuk membuat dan beralih ke cabang baru:
     ```
     git checkout -b nama_cabang
     ```

3. **Lakukan Perubahan:**
   - Setiap anggota tim dapat melakukan perubahan pada kode di dalam cabang mereka sesuai dengan tugas atau fitur yang ditugaskan.

4. **Commit dan Push:**
   - Setelah melakukan perubahan, Anda harus melakukan commit untuk menyimpan perubahan tersebut secara lokal, dan kemudian push perubahan ke repo proyek di server. Gunakan perintah berikut:
     ```
     git add .
     git commit -m "Pesan commit Anda di sini"
     git push origin nama_cabang
     ```

5. **Pull Request (PR):**
   - Setelah push perubahan ke repo, anggota tim dapat membuat Pull Request untuk meminta pemilik repo untuk menggabungkan perubahan mereka ke dalam cabang utama proyek.

6. **Review dan Diskusi:**
   - Tim dapat memberikan review pada Pull Request, melakukan perubahan jika diperlukan, dan berdiskusi tentang perubahan yang diajukan.

7. **Merge Pull Request:**
   - Setelah Pull Request diulas dan disetujui, pemilik repo atau pengelola proyek dapat menggabungkan (merge) perubahan tersebut ke dalam cabang utama proyek.

8. **Sinkronisasi dengan Cabang Utama (Branch):**
    - Agar selalu mengikuti perubahan terbaru di cabang utama proyek, anggota tim dapat melakukan pull dari cabang utama (`git pull origin main`) secara teratur.

   **Link:**
    - https://rycs123.github.io/KPP_BMS_KantinC.github.io/
