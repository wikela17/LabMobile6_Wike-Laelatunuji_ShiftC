Bagaimana cara untuk menambahkan Komponen di halaman Ionic? Jelaskan secara detail langkahnya.

 Langkah 1: Persiapkan Proyek Ionic
1.	Buat Proyek Ionic Baru di terminal
ionic start tugas6   
2.	Buka folder Pada VSCode lalu pada terminal ketikkan
ionic serve

 Langkah 2: Tambahkan Komponen ke Halaman
1.	Buka File Halaman yang ingin Anda tambahkan komponen, misalnya home.page.html.
2.	Tambahkan Komponen yang diinginkan ke dalam file HTML. Contoh menambahkan ion-card:
   ```
<ion-content>
  <ion-card>
    <ion-card-header>
      <ion-card-title>Profil Mahasiswa</ion-card-title>
    </ion-card-header>
    <ion-card-content>
      <h1>Wike Laelatunuji</h1>
      <h2>H1D022107</h2>
    </ion-card-content>
  </ion-card>
</ion-content>
```
Langkah 3: Styling Komponen
1.	Buka File SCSS yang sesuai, misalnya home.page.scss.
2.	Tambahkan Styling sesuai kebutuhan. Contoh:
ion-card {
  margin: 20px;
  border-radius: 15px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

ion-card-title {
  font-size: 1.5em;
  color: #6a1b9a;
}
Langkah 4: Jalankan Aplikasi
Setelah menambahkan komponen dan styling, jalankan kembali aplikasi untuk melihat perubahan:
ionic serve

screenshoot tampilan:

![Screenshot 2024-10-26 152929](https://github.com/user-attachments/assets/fcd810c4-c164-430c-a94e-5f979337dc7a)


