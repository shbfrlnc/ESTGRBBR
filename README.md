# ESTGRBBR

ESTGRBBR adalah aplikasi website downloader, yang hasilnya PDF atau gambar.

Untuk mendownloadnya, kunjungi bagian Releases.

Untuk menjalankannya, ekstrak file zipnya, kemudian jalankan:

```
npm install
```

Kemudian, jalankan:

```
npm run dev // untuk menjalankan aplikasi dengan script plaintext
```

Atau

```
npm run obfuscate
npm run start // untuk menjalankan aplikasi dengan script yang sudah di-obfuscate
```

Untuk mem-build aplikasi ini menjadi installer (aplikasi Windows):

```
npm run obfuscate // obfuscate dulu, karena yang di production bukan dalam bentuk plaintext
npm run dist // build installer, hasilnya ada di ../_Release/ESTGRBBR
```

Catatan:

- Fitur proxy belum dicoba, silakan coba sendiri, tapi resiko Anda tanggung sendiri.

## Info Tambahan

Traktir Saya:

https://sociabuzz.com/lsfkrshb/tribe

Channel YouTube Saya:

https://www.youtube.com/c/shbfrlnc
