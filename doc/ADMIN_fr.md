- Votre Faircamp est installé dans `__INSTALL_DIR__`
- Votre contenu doit être dans `__INSTALL_DIR__/content`
- Votre fichier de configuration est `__INSTALL_DIR__/content/catalog.eno` (voir [la doc](https://simonrepp.com/faircamp/manual/manifests.html))
- Le site sera automatiquement mis à jour à chaque fois que vous modifierez quelque chose dans le dossier `content` !

Si vous avez besoin de générer le site à la main :

- `sudo -u __APP__ "__INSTALL_DIR__/faircamp" --build-dir "__INSTALL_DIR__/www" --catalog-dir "__INSTALL_DIR__/content"`

ou

- `sudo yunohost app shell __APP__`
- `./faircamp --build-dir ./www --catalog-dir ./content`
