## Indonesia Language Pack for [Flarum](http://flarum.org/)

Paket bahasa Indonesia untuk melokalisasi Flarum

## Informasi
**Version**:  1.0.2-dev | **Requires**: Flarum 0.1.0 Beta 5 | **Compatible up to**: Flarum 0.1.0 Beta 5

 - Belum semuanya diterjemahkan dengan benar dan masih ada beberapa yang
   belum diterjemahkan.
 - Teks bahasa Inggris masih ada dalam bentuk yaml komentar. Harapannya, ketika Anda ingin membantu saya, Anda bisa mengerjakannya dengan mudah.

### Cara Menggunakan
1. [Download](https://github.com/realodix/flarum-indonesian/archive/master.zip).
2. Ekstrak dan upload ke dalam folder **vendor\flarum**.
3. Ubah nama folder **flarum-ext-indonesian-master** menjadi **flarum-ext-indonesian**.
4. Buka file **vendor\composer\installed.json** dan tambahkan ini

    {
        "name": "flarum/flarum-ext-indonesian",
        "version": "v1.0.2-dev",
        "require": {
            "flarum/core": "^0.1.0-beta.5"
        },
        "type": "flarum-extension",
        "extra": {
            "branch-alias": {
                "dev-master": "0.1.x-dev"
            },
            "flarum-extension": {
                "title": "Indonesian",
                "icon": {
                    "image": "icon.svg",
                    "backgroundColor": "#00247d",
                    "backgroundSize": "cover",
                    "backgroundPosition": "center"
                }
            },
            "flarum-locale": {
                "code": "id",
                "title": "Indonesian"
            }
        },
        "license": [
            "MIT"
        ],
        "description": "Indonesian language pack.",
        "keywords": [
            "locale"
        ]
    }

5. Masuk ke halamam admin Flarum, klik **Extensions**.
6. Aktifkan.

### License
Released under the MIT License. Please see the [LICENSE](https://github.com/realodix/flarum-ext-indonesian/blob/master/LICENSE) file.