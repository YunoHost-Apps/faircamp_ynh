<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Faircamp para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/faircamp.svg)](https://ci-apps.yunohost.org/ci/apps/faircamp/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/faircamp.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/faircamp.maintain.svg)

[![Instalar Faircamp con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=faircamp)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarFaircamp rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Faircamp is a [Static Site Generator](https://en.wikipedia.org/wiki/Static_site_generator) dedicated to music producers.

With this package, Faircamp will automatically regenerate ([using Systemd Path Units](https://www.putorius.net/systemd-path-units.html)) your website if any change is made to your sources.

Alternatively to this package, you can [install Faircamp on your computer](https://simonrepp.com/faircamp/manual/installation.html) and use its rsync feature (ith the `--deploy` or `--deploy-destination` options) to send the builded website to a [My Webapp](https://apps.yunohost.org/app/my_webapp) folder on your YunoHost server.


**Versión actual:** 0.17.0~ynh1

## Capturas

![Captura de Faircamp](./doc/screenshots/faircamp-screenshot.png)

## Documentaciones y recursos

- Sitio web oficial: <https://simonrepp.com/faircamp/>
- Documentación administrador oficial: <https://simonrepp.com/faircamp/manual/>
- Repositorio del código fuente oficial de la aplicación : <https://codeberg.org/simonrepp/faircamp>
- Catálogo YunoHost: <https://apps.yunohost.org/app/faircamp>
- Reportar un error: <https://github.com/YunoHost-Apps/faircamp_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing --debug
o
sudo yunohost app upgrade faircamp -u https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
