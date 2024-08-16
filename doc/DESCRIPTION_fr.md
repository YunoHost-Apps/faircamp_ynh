Faircamp est un [générateur de site statique](https://fr.wikipedia.org/wiki/G%C3%A9n%C3%A9rateur_de_site_statique) dédiée aux producteurices de musique.

Avec ce package, Faircamp régénérera automatiquement ([à l'aide de Systemd Path Units](https://www.putorius.net/systemd-path-units.html)) votre site web si une modification est apportée à vos sources.

En alternative à ce package, vous pouvez [installer Faircamp sur votre ordinateur](https://simonrepp.com/faircamp/manual/installation.html) et utiliser sa fonction rsync (avec les options `--deploy` ou `--deploy-destination`) pour envoyer le site web généré dans un dossier [My Webapp](https://apps.yunohost.org/app/my_webapp) sur votre serveur YunoHost.
