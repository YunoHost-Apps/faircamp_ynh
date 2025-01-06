<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Faircamp voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/faircamp)](https://ci-apps.yunohost.org/ci/apps/faircamp/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/faircamp)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/faircamp)

[![Faircamp met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=faircamp)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Faircamp snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Faircamp is a [Static Site Generator](https://en.wikipedia.org/wiki/Static_site_generator) dedicated to music producers.

With this package, Faircamp will automatically regenerate ([using Systemd Path Units](https://www.putorius.net/systemd-path-units.html)) your website if any change is made to your sources.

Alternatively to this package, you can [install Faircamp on your computer](https://simonrepp.com/faircamp/manual/installation.html) and use its rsync feature (ith the `--deploy` or `--deploy-destination` options) to send the builded website to a [My Webapp](https://apps.yunohost.org/app/my_webapp) folder on your YunoHost server.


**Geleverde versie:** 1.0.0~ynh2

## Schermafdrukken

![Schermafdrukken van Faircamp](./doc/screenshots/faircamp-screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://simonrepp.com/faircamp/>
- Officiele beheerdersdocumentatie: <https://simonrepp.com/faircamp/manual/>
- Upstream app codedepot: <https://codeberg.org/simonrepp/faircamp>
- YunoHost-store: <https://apps.yunohost.org/app/faircamp>
- Meld een bug: <https://github.com/YunoHost-Apps/faircamp_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing --debug
of
sudo yunohost app upgrade faircamp -u https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
