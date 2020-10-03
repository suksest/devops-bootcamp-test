# Studi Kasus: FTP

# FTP
FTP merupakan protokol transfer data berbasis file manager. Sehingga file yang ditransfer ke _client_ tidak akan dipindahkan ke server. Selain itu salah satu keunggulan FTP adalah. Kita dapat melanjutkan proses download yang sebelumnya terhenti.FTP juga mendukung transfer file yang berukuran besar.

Akses ke FTP maka bisa dilakukan dengan tahapan berikut.

## Langkah-langkah

1. Connect ke ftp server. Setelah mengeksekusi perintah ini, mungkin saja perlu dimasukkan password yang berkaitan dengan `username`
```shell
ftp {username}@{host}
```

2. Download file
```shell
get {nama_file}
```

# SFTP
Selain menggunakan FTP juga bisa menggunakan SFTP. SFTP merupakan service FTP yang berjalan dengan melalui protocol SSH. Sehingga transfer data menggunakan SFTP lebih aman bila dibandingkan dengan FTP. Download file melalui FTP bisa dilakukan dengan tahapan berikut.

## Langkah-langkah

1. Connect melalui protokol ssh
```shell
sftp {username}@{host}
```

2. Download file
```shell
get {nama_file}
```
