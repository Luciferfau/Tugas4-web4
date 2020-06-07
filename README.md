# Tugas4-web4
Tugas pemograman web dasar 4 yang ke-1 (code-logout.php)

<?php 
    session_start();
    echo "<script>alert('Berhasil Logout');window.location=('index.php')</script>";
    session_destroy();
?>

Penjelasan :
script menunjukan alarm atau peringatan bahwa pengguna telah berhasil logout dari halaman tersebut.
script menggunakan php.
