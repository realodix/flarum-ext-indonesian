## Indonesia Language Pack for [Flarum](http://flarum.org/)

Paket bahasa Indonesia untuk Flarum dan beberapa ekstensi yang [didukung](#extensi-yang-didukung).

## Informasi
[![GitHub tag](https://img.shields.io/github/tag/realodix/flarum-ext-indonesian.svg)](https://GitHub.com/realodix/flarum-ext-indonesian/tags/)
[![Latest Unstable Version](https://poser.pugx.org/realodix/flarum-ext-indonesian/v/unstable)](https://github.com/realodix/flarum-ext-indonesian/archive/master.zip)
[![License](https://poser.pugx.org/realodix/flarum-ext-indonesian/license)](https://github.com/realodix/flarum-ext-indonesian/blob/master/LICENSE)

**Requires**: [Flarum v1.5.0](https://github.com/flarum/core/releases/tag/v1.5.0) <br>
**Compatible up to**: [Flarum v1.5.0](https://github.com/flarum/core/releases/tag/v1.5.0)

### Cara Memasang
Flarum mengandalkan [Composer](https://getcomposer.org/) untuk mengelola dependensi dan ekstensi. Paket bahasa Indonesia tersedia di [Packagist](https://packagist.org/packages/realodix/flarum-ext-indonesian) dan dapat dikelola dengan cara di bawah ini. Pastikan Composer sudah terinstall di komputer Anda, lalu ikuti langkah berikut ini:

1. Jalankan perintah ini pada folder Anda menginstall Flarum

   ```sh
   composer require realodix/flarum-ext-indonesian
   ```

   Jika Anda ingin menginstall versi tidak stabil, maka jalankan perintah ini

   ```sh
   composer require realodix/flarum-ext-indonesian dev-master
   ```

2. Masuk ke halamam admin Flarum, klik **Extensions**, lalu centang **Indonesian**.

Perintah yang sama (pada langkah 1) dapat digunakan untuk memperbarui secara mandiri paket bahasa Indonesia (tanpa mempengaruhi paket lainnya). Perhatikan bahwa karena paket bahasa Indonesia akan ditambahkan sebagai dependensi Flarum, maka akan secara otomatis diperbarui ketika Anda memperbarui Flarum dan dependensinya melalui Composer.

### Extensi Yang Didukung
Ketika Anda menginstall salah satu atau semua ekstensi yang ada pada daftar di bawah ini, maka semua kalimat pada ekstensi tersebut akan ikut diterjemahkan ke dalam bahasa Indonesia.

- [afrux/news-widget](https://github.com/afrux/news-widget) v0.1.1
- [afrux/online-users-widget](https://github.com/afrux/online-users-widget) v0.1.6
- [fof/analytics](https://github.com/friendsofflarum/analytics) v1.0.0
- [fof/custom-footer](https://github.com/friendsofflarum/custom-footer) v1.0.1
- [fof/doorman](https://github.com/FriendsOfFlarum/doorman) v1.1.1
- [fof/drafts](https://github.com/FriendsOfFlarum/drafts) v1.1.2
- [fof/filter](https://github.com/FriendsOfFlarum/filter) v1.1.1
- [fof/formatting](https://github.com/friendsofflarum/formatting) v1.0.2
- [fof/forum-statistics-widget](https://github.com/FriendsOfFlarum/forum-statistics-widget) v1.0.1
- [fof/impersonate](https://github.com/FriendsOfFlarum/impersonate) v1.1.0
- [fof/links](https://github.com/FriendsOfFlarum/links) v1.1.2
- [fof/merge-discussions](https://github.com/friendsofflarum/merge-discussions) v1.3.1
- [fof/moderator-notes](https://github.com/FriendsOfFlarum/moderator-notes) v1.1.0
- [fof/nightmode](https://github.com/friendsofflarum/nightmode) v1.4.1
- [fof/polls](https://github.com/friendsofflarum/polls) v1.1.0
- [fof/prevent-necrobumping](https://github.com/friendsofflarum/prevent-necrobumping) v1.1.0
- [fof/reactions](https://github.com/friendsofflarum/reactions) v1.1.2
- [fof/secure-https](https://github.com/friendsofflarum/secure-https) v1.1.0
- [fof/sitemap](https://github.com/FriendsOfFlarum/sitemap) v2.0.1
- [fof/socialprofile](https://github.com/FriendsOfFlarum/socialprofile) v1.1.4
- [fof/spamblock](https://github.com/friendsofflarum/spamblock) v1.0.1
- [fof/stopforumspam](https://github.com/friendsofflarum/stopforumspam) v0.2.2
- [fof/subscribed](https://github.com/friendsofflarum/subscribed) v1.1.2
- [fof/upload](https://github.com/friendsofflarum/upload) v1.2.3
- [fof/user-bio](https://github.com/friendsofflarum/user-bio) v1.1.0
- [fof/user-directory](https://github.com/friendsofflarum/user-directory) v1.2.3
- [fof/username-request](https://github.com/friendsofflarum/username-request) v1.0.1
- [justoverclockl/staff-member-widget](https://github.com/justoverclockl/staff-member-widget) v0.1.3
- [SychO9/flarum-profile-cover](https://github.com/SychO9/flarum-profile-cover) v1.3.3


### Catatan
- Sejauh ini sudah hampir 100% diterjemahkan.
- Beberapa kalimat diterjemahkan dengan bahasa tidak baku. Sebagai contoh kata _password_ tetap Saya tulis _password_ (harusnya kata sandi, dan kata _upload_ tetap Saya tulis _upload_ (harusnya unggah).
- Teks bahasa Inggris masih ada dalam bentuk komentar yaml, diharapkan Anda bisa dengan mudah membantu Saya untuk mengkoreksi terjemahan yang sudah ada.

## Berkontribusi
Terima kasih banyak untuk Anda yang ingin berkontribusi. Saya sangat menghargai komitmen Anda. Menggunakan paket bahasa sudah merupakan dukungan besar, tetapi cara terbaik lainnya untuk berkontribusi adalah:

- Beri kami bintang/star di [GitHub](https://github.com/realodix/flarum-ext-indonesian). Karena jika Anda menggunakan dan menyukainya, Anda setidaknya bisa menjadi stargazer!
- Follow kami di [GitHub](https://github.com/realodix/flarum-ext-indonesian). Anda akan mendapatkan pemberitahuan secara real time dari semua perubahan. Tidak ada yang terlewat!
- [Laporkan masalah](https://github.com/realodix/flarum-ext-indonesian/issues) di GitHub. Semua umpan balik diterima.
- Open pull requests di [GitHub](https://github.com/realodix/flarum-ext-indonesian) untuk memberikan perbaikan dan peningkatan. Otomatis terdaftar sebagai [kontributor](https://github.com/realodix/flarum-ext-indonesian/graphs/contributors)!
- Ikut ngobrol di [diskusi Indonesian Language Pack](https://discuss.flarum.org/d/1358-indonesian-language-pack).
- Mari kita kopdar jika Anda sedang berada di dekat Jakarta!


## License
Released under the MIT License. Please see the [license](https://github.com/realodix/flarum-ext-indonesian/blob/master/LICENSE) file.
