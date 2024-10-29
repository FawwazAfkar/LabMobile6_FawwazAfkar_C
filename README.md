# Cara Menambahkan Komponen ke `home.page.html`

Berikut adalah langkah-langkah untuk menambahkan komponen ke `home.page.html` dari dokumentasi web Ionic:

1. **Buka Dokumentasi Ionic**:
    Buka [Ionic Framework Documentation](https://ionicframework.com/docs) untuk mencari komponen yang ingin ditambahkan.

2. **Pilih Komponen**:
    Pilih komponen yang ingin ditambahkan, misalnya disini saya ambil `ion-card`.

3. **Salin Kode Komponen**:
    Salin kode HTML dari komponen yang dipilih. Contoh yang saya ambil yaitu `ion-card`:
    ```html
    <ion-card>
  <img alt="Silhouette of mountains" src="https://ionicframework.com/docs/img/demos/card-media.png" />
  <ion-card-header>
    <ion-card-title>Card Title</ion-card-title>
    <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
  </ion-card-header>

  <ion-card-content>
    Here's a small text description for the card content. Nothing more, nothing less.
  </ion-card-content>
</ion-card>
    ```

4. **Buka `home.page.html`**:
    Buka file `home.page.html`.

5. **Tempel Kode Komponen**:
    Tempel kode komponen yang telah disalin ke dalam file `home.page.html` dan lakukan beberapa penyesuaian.
    ```html
    <ion-header [translucent]="true">
    <ion-toolbar>
        <ion-title>
        Profil
        </ion-title>
    </ion-toolbar>
    </ion-header>

    <ion-content [fullscreen]="true">
    <ion-header collapse="condense">
        <ion-toolbar>
        <ion-title size="large">Profil</ion-title>
        </ion-toolbar>
    </ion-header>

    <div id="container">
        <ion-card>
        <img alt="waz" src="assets/img/waz.jpg" />
        <ion-card-header>
            <ion-card-title>Fawwaz Afkar Muzakky</ion-card-title>
            <ion-card-subtitle>H1D022067</ion-card-subtitle>
        </ion-card-header>
        
        <ion-card-content>
            <p>I'm a 3rd year student at Informatics</p>
            <ion-chip color="dark">Jenderal Soedirman University</ion-chip>
        </ion-card-content>
        </ion-card>
    </div>
    </ion-content>

    ```

6. **Lihat Hasil**:
    Jalankan aplikasi Ionic dengan perintah `ionic s` untuk melihat komponen yang telah ditambahkan.

# Hasil
![Screenshot](assets/img/image.png)

