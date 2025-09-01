# tugas-PWEB
membuat profil
#Profil dengan Semua Elemen
##Buat halaman profil.html.
##Isi harus memuat:
Judul profil (heading)
Paragraf deskripsi diri
Foto profil (image)
Daftar hobi (list)
Tabel riwayat pendidikan
Form kontak sederhana+
Link ke media sosial

```
<!DOCTYPE html>
<html>
<head>
    <title>Profil Saya</title>
</head>
<body>
    <h1 style="text-align: center;">Profil Mahasiswa</h1>

    <p>Halo! Nama saya <b>Muhammad Rivaldi Sholihin</b>. Saya seorang mahasiswa jurusan Teknik Informatika 
    yang tertarik pada pengembangan web dan pemrograman.</p>

    <img src="c:\Users\rival\OneDrive\Pictures\wp_chomr\life plan_sampul.jpeg" alt="Foto Profil" width="200">

    <h2>Hobi Saya:</h2>
    <ul>
        <li>Bersepeda</li>
        <li>main game</li>
        <li>membaca</li>
    </ul>

    <h2>Pendidikan</h2>
    <table border="1" cellpadding="5">
        <tr>
            <th>Tahun</th>
            <th>Sekolah</th>
        </tr>
        <tr>
            <td>2021 - 2024</td>
            <td>SMA Negeri 1 Kraksaan</td>
        </tr>
        <tr>
            <td>2021 - Sekarang</td>
            <td>Institut Teknologi Informatika</td>
        </tr>
    </table>

    <h2>Kontak Saya</h2>
    <form>
        <label>Nama:</label><br>
        <input type="text" name="nama" size="30" value="Muhammad Rivaldi Sholihin"><br><br>

        <label>Email:</label><br>
        <input type="email" name="email" size="30" value="rivaldi.sholihin@gmail.com"><br><br>

        <label>Pesan:</label><br>
        <textarea name="pesan" rows="4" cols="30">Lorem ipsum dolor sit amet, 
            consectetur adipisicing elit. Nisi doloremque, quaerat tenetur fuga 
            perferendis deserunt nemo porro voluptates error facilis corrupti 
            velit cum aperiam. Praesentium rem quidem vitae doloremque quia?
        </textarea>
    
        <br><br>

        <input type="submit" value="Kirim">
    </form>

    <p>Kunjungi <a href="https://github.com/Rivaldi42">GitHub</a> saya untuk melihat project.</p>
</body>
</html>
```
##Screenshoot
https://drive.google.com/file/d/1kHO84anrkAYrvCyLZ8U1lMTGyJBaX5ed/view?usp=sharing
