<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Faircamp pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/zola.svg)](https://ci-apps.yunohost.org/ci/apps/zola/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/zola.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/zola.maintain.svg)

[![Installer Faircamp avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=faircamp)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Faircamp rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Faircamp est un [générateur de site statique](https://fr.wikipedia.org/wiki/G%C3%A9n%C3%A9rateur_de_site_statique) dédiée aux producteurices de musique.

Avec ce package, Faircamp régénérera automatiquement ([à l'aide de Systemd Path Units](https://www.putorius.net/systemd-path-units.html)) votre site web si une modification est apportée à vos sources.


**Version incluse :** 0.15.1~ynh1

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
