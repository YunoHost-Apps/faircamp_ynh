<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Faircamp pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/faircamp)](https://ci-apps.yunohost.org/ci/apps/faircamp/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/faircamp)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/faircamp)

[![Installer Faircamp avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=faircamp)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Faircamp rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Faircamp est un [générateur de site statique](https://fr.wikipedia.org/wiki/G%C3%A9n%C3%A9rateur_de_site_statique) dédiée aux producteurices de musique.

Avec ce package, Faircamp régénérera automatiquement ([à l'aide de Systemd Path Units](https://www.putorius.net/systemd-path-units.html)) votre site web si une modification est apportée à vos sources.

En alternative à ce package, vous pouvez [installer Faircamp sur votre ordinateur](https://simonrepp.com/faircamp/manual/installation.html) et utiliser sa fonction rsync (avec les options `--deploy` ou `--deploy-destination`) pour envoyer le site web généré dans un dossier [My Webapp](https://apps.yunohost.org/app/my_webapp) sur votre serveur YunoHost.


**Version incluse :** 1.0.0~ynh2

## Captures d’écran

![Capture d’écran de Faircamp](./doc/screenshots/faircamp-screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://simonrepp.com/faircamp/>
- Documentation officielle de l’admin : <https://simonrepp.com/faircamp/manual/>
- Dépôt de code officiel de l’app : <https://codeberg.org/simonrepp/faircamp>
- YunoHost Store : <https://apps.yunohost.org/app/faircamp>
- Signaler un bug : <https://github.com/YunoHost-Apps/faircamp_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing --debug
ou
sudo yunohost app upgrade faircamp -u https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
