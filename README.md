## Indonesia Language Pack for [Flarum](http://flarum.org/)

Paket bahasa Indonesia untuk Flarum dan beberapa ekstensi yang [didukung](#extensi-yang-didukung).

## Informasi
[![Latest Stable Version](https://poser.pugx.org/realodix/flarum-ext-indonesian/v/stable)](https://github.com/realodix/flarum-ext-indonesian)
[![Latest Unstable Version](https://poser.pugx.org/realodix/flarum-ext-indonesian/v/unstable)](https://github.com/realodix/flarum-ext-indonesian/archive/master.zip)
[![License](https://poser.pugx.org/realodix/flarum-ext-indonesian/license)](https://github.com/realodix/flarum-ext-indonesian/blob/master/LICENSE)

**Requires**: Flarum 0.1.0-beta.10 | **Compatible up to**: Flarum 0.1.0-beta.11

### Cara Memasang
Flarum mengandalkan [Composer](https://getcomposer.org/) untuk mengelola dependensi dan ekstensi. Paket bahasa Indonesia tersedia di [Packagist](https://packagist.org/packages/realodix/flarum-ext-indonesian) dan dapat dikelola dengan cara di bawah ini. Pastikan Composer sudah terinstall di komputer Anda, lalu ikuti langkah berikut ini:

1. Jalankan perintah ini pada folder Anda menginstall Flarum

       composer require realodix/flarum-ext-indonesian

    Jika Anda ingin menginstall versi tidak stabil, maka jalankan perintah ini

       composer require realodix/flarum-ext-indonesian dev-master

2. Masuk ke halamam admin Flarum, klik **Extensions**, lalu centang **Indonesian**.

Perintah yang sama (pada langkah 1) dapat digunakan untuk memperbarui secara mandiri paket bahasa Indonesia (tanpa mempengaruhi paket lainnya). Perhatikan bahwa karena paket bahasa Indonesia akan ditambahkan sebagai dependensi Flarum, maka akan secara otomatis diperbarui ketika Anda memperbarui Flarum dan dependensinya melalui Composer.

### Extensi Yang Didukung
Ketika Anda menginstall salah satu atau semua ekstensi yang ada pada daftar di bawah ini, maka semua kalimat pada ekstensi tersebut akan ikut diterjemahkan ke dalam bahasa Indonesia.

- [datitisev/flarum-ext-dashboard](https://github.com/datitisev/flarum-ext-dashboard) v0.1.0-beta.8.1
- [extiverse/bazaar](https://github.com/extiverse/bazaar) v0.4.1
- [flagrow/impersonate](https://github.com/flagrow/impersonate) v0.3.0
- [flagrow/users-list](https://github.com/flagrow/users-list) v0.1.2
- [friendsofflarum/ads](https://github.com/friendsofflarum/ads) v0.2.4
- [friendsofflarum/analytics](https://github.com/friendsofflarum/analytics) v0.8.0
- [friendsofflarum/byobu](https://github.com/friendsofflarum/byobu) v0.4.1
- [friendsofflarum/custom-footer](https://github.com/friendsofflarum/custom-footer) v0.1.3
- [friendsofflarum/formatting](https://github.com/friendsofflarum/formatting) v0.1.4
- [friendsofflarum/gamification](https://github.com/friendsofflarum/gamification) v0.1.6
- [friendsofflarum/masquerade](https://github.com/friendsofflarum/masquerade) v0.3.3
- [friendsofflarum/merge-discussions](https://github.com/friendsofflarum/merge-discussions) v0.3.3
- [friendsofflarum/pages](https://github.com/friendsofflarum/pages) v0.2.7
- [friendsofflarum/polls](https://github.com/friendsofflarum/polls) v0.1.1
- [friendsofflarum/prevent-necrobumping](https://github.com/friendsofflarum/prevent-necrobumping) v0.2.0
- [friendsofflarum/reactions](https://github.com/friendsofflarum/reactions) v0.1.0
- [friendsofflarum/secure-https](https://github.com/friendsofflarum/secure-https) v0.1.0
- [friendsofflarum/spamblock](https://github.com/friendsofflarum/spamblock) v0.2.1
- [friendsofflarum/split](https://github.com/friendsofflarum/split) v0.4.3
- [friendsofflarum/subscribed](https://github.com/friendsofflarum/subscribed) v0.1.1
- [friendsofflarum/upload](https://github.com/friendsofflarum/upload) v0.7.1
- [friendsofflarum/user-bio](https://github.com/friendsofflarum/user-bio) v0.1.3
- [friendsofflarum/user-directory](https://github.com/friendsofflarum/user-directory) v0.3.3
- [friendsofflarum/username-request](https://github.com/friendsofflarum/username-request) v0.2.0
- [kilowhat/flarum-ext-mailing](https://github.com/kilowhat/flarum-ext-mailing) v0.1.1
- [michaelbelgium/flarum-discussion-views](https://github.com/michaelbelgium/flarum-discussion-views) v0.1.0-beta.8.2
- [michaelbelgium/flarum-profile-views](https://github.com/michaelbelgium/flarum-profile-views) v2.1.6
- [michaelbelgium/mybb_to_flarum](https://github.com/michaelbelgium/mybb_to_flarum) v4.1
- [oaklinq/flarum-ext-reply2see](https://github.com/oaklinq/flarum-ext-reply2see) v0.1.2
- [reflar/level-ranks](https://github.com/reflar/level-ranks) v1.2.1
- [wiwatsrt/flarum-ext-best-answer](https://github.com/wiwatsrt/flarum-ext-best-answer) v0.2.4

### Catatan
- Sejauh ini sudah hampir 100% diterjemahkan.
- Beberapa kalimat diterjemahkan dengan bahasa tidak baku. Sebagai contoh kata _password_ tetap Saya tulis _password_ (harusnya kata sandi), dan kata _upload_ tetap Saya tulis _upload_ (harusnya unggah).
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
