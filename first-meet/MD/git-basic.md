# Git Dasar

![fire](../img/git-basic.jpg)



## Perintah Git Dasar

1. Membuat Repo: `git init` yang akan membuat folder .git (biasanya hidden folder)
2. Mengecek Status: `git status` untuk mengecek status pada repo kita
3. Menandai Perubahan: `git add` untuk menaikan ke area on staging
4. Menyimpan Perubahan: `git commit` untuk memberikan pesan di setiap commitan 
5. Melihat Daftar Commit: `git log`



## Membuat Repositori

Repositori adalah direktori projek / tempat kita bekerja yang menggunakan Git.

Cara membuat Repositori:

1. `git init belajar-git`
2. `git init`



## Tiga Kondisi File

Di Git, terdapat 3 kondisi file yang harus diketahui:

1. **Modified**: Terdapat perubahan atau penambahan file.
2. **Staged**: Kondisi file sudah ditandai namun belum disimpan.
3. **Commited**: Kondifisi file sudah disimpan di VCS.



## Membuat Revisi atau Perubahan

1. Buat file Index.html
2. Cek status repositori: `git status`
3. Ubah kondisi menjadi **Stage**: `git add index.html`
4. Cek status repositori: `git status`
5. Ubah kondisi menjadi **Commit**: `git commit -m "pesan commit"`



## Melihat Log Revisi

1. `git log`