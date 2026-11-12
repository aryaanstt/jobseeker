# Jobseeker

Aplikasi pribadi untuk mencari loker fresh graduate di Indonesia, menilai kecocokannya, menyiapkan paket lamaran, dan melacak status lamaran.

- Buka: https://aryaanstt.github.io/jobseeker/
- Halaman ini mengarah ke aplikasi yang berjalan sebagai halaman pribadi di Claude. Hanya pemiliknya yang bisa membuka isinya.
- Kode tampilan aplikasi ada di `app/jobseeker.html`. Data loker dan lamaran tidak disimpan di repo ini.

## Cara kerja
1. Loker dicari dari situs karier resmi, career center kampus, dan portal lowongan, lalu diverifikasi ke sumber resmi.
2. Tiap loker disaring (IPK, deadline, syarat tegas) dan diberi nilai kecocokan 1 sampai 5.
3. Loker yang cocok dibuatkan paket lamaran: jawaban tiap kolom form yang diambil hanya dari fakta yang benar-benar dikerjakan, tanpa klaim tambahan.
4. Pengguna mengecek paket, mengisi form, dan menekan submit sendiri.
5. Status lamaran dicatat dari daftar sampai hasil akhir.
