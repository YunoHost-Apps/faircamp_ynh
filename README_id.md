<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Faircamp untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/faircamp.svg)](https://ci-apps.yunohost.org/ci/apps/faircamp/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/faircamp.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/faircamp.maintain.svg)

[![Pasang Faircamp dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=faircamp)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Faircamp secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Faircamp is a [Static Site Generator](https://en.wikipedia.org/wiki/Static_site_generator) dedicated to music producers.

With this package, Faircamp will automatically regenerate ([using Systemd Path Units](https://www.putorius.net/systemd-path-units.html)) your website if any change is made to your sources.

Alternatively to this package, you can [install Faircamp on your computer](https://simonrepp.com/faircamp/manual/installation.html) and use its rsync feature (ith the `--deploy` or `--deploy-destination` options) to send the builded website to a [My Webapp](https://apps.yunohost.org/app/my_webapp) folder on your YunoHost server.


**Versi terkirim:** 0.20.1~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Faircamp](./doc/screenshots/faircamp-screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://simonrepp.com/faircamp/>
- Dokumentasi admin resmi: <https://simonrepp.com/faircamp/manual/>
- Depot kode aplikasi hulu: <https://codeberg.org/simonrepp/faircamp>
- Gudang YunoHost: <https://apps.yunohost.org/app/faircamp>
- Laporkan bug: <https://github.com/YunoHost-Apps/faircamp_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing --debug
atau
sudo yunohost app upgrade faircamp -u https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
