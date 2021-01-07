# docker container
1. membuat docker hub dengan Buka halaman web 
   https://hub.docker.com/
2. Membuat Docker Container dengan docker file
   Buka aplikasi Docker Toolbox. Buat direktori dengan nama folder nim anda di dalam direktori C:\Program Files\Docker Toolbox.
3. Buat file dengan nama Dockerfile didalam direktori nim yang anda buat.
4. Buat direktori dengan nama files didalam direktori nim yang anda buat.
5. Buat file default.conf didalam direktori files.
6. Buat file index.html di dalam direktori files. Isikan kode untuk menampilkan nama dan nim anda ke dalam index.html
7. Buat file dengan nama nginx.conf di dalam ditektori files. Isikan kode berikut kedalam file nginx.conf
8. Buka aplikasi Docker Toolbox kemudian masuk pada direktori nim yang anda buat sebelumnya
9. Jalankan perintah “docker build -t nama-nimanda .”
10. Jalankan perintah “docker images” untuk melihat image yang ada
11. Ketika jalankan image tersebut menjadi container. Ketikan perintah “ docker run -d -p 8000:80 –name nim-nama namaimage”
12. Buka web browser anda ketikkan url http://192.168.99.100:8000/. Jika web yang tampil nama dan nim maka sukses di buat
13. Build image menggunakan github ke docker hub
