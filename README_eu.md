<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Faircamp YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/faircamp.svg)](https://ci-apps.yunohost.org/ci/apps/faircamp/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/faircamp.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/faircamp.maintain.svg)

[![Instalatu Faircamp YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=faircamp)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Faircamp YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Faircamp is a [Static Site Generator](https://en.wikipedia.org/wiki/Static_site_generator) dedicated to music producers.

With this package, Faircamp will automatically regenerate ([using Systemd Path Units](https://www.putorius.net/systemd-path-units.html)) your website if any change is made to your sources.

Alternatively to this package, you can [install Faircamp on your computer](https://simonrepp.com/faircamp/manual/installation.html) and use its rsync feature (ith the `--deploy` or `--deploy-destination` options) to send the builded website to a [My Webapp](https://apps.yunohost.org/app/my_webapp) folder on your YunoHost server.


**Paketatutako bertsioa:** 0.19.0~ynh1

## Pantaila-argazkiak

![Faircamp(r)en pantaila-argazkia](./doc/screenshots/faircamp-screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://simonrepp.com/faircamp/>
- Administratzaileen dokumentazio ofiziala: <https://simonrepp.com/faircamp/manual/>
- Jatorrizko aplikazioaren kode-gordailua: <https://codeberg.org/simonrepp/faircamp>
- YunoHost Denda: <https://apps.yunohost.org/app/faircamp>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/faircamp_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing --debug
edo
sudo yunohost app upgrade faircamp -u https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
