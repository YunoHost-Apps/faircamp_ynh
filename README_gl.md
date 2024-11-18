<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Faircamp para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/faircamp.svg)](https://ci-apps.yunohost.org/ci/apps/faircamp/) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/faircamp.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/faircamp.maintain.svg)

[![Instalar Faircamp con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=faircamp)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Faircamp de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Faircamp is a [Static Site Generator](https://en.wikipedia.org/wiki/Static_site_generator) dedicated to music producers.

With this package, Faircamp will automatically regenerate ([using Systemd Path Units](https://www.putorius.net/systemd-path-units.html)) your website if any change is made to your sources.

Alternatively to this package, you can [install Faircamp on your computer](https://simonrepp.com/faircamp/manual/installation.html) and use its rsync feature (ith the `--deploy` or `--deploy-destination` options) to send the builded website to a [My Webapp](https://apps.yunohost.org/app/my_webapp) folder on your YunoHost server.


**Versión proporcionada:** 0.21.0~ynh1

## Capturas de pantalla

![Captura de pantalla de Faircamp](./doc/screenshots/faircamp-screenshot.png)

## Documentación e recursos

- Web oficial da app: <https://simonrepp.com/faircamp/>
- Documentación oficial para admin: <https://simonrepp.com/faircamp/manual/>
- Repositorio de orixe do código: <https://codeberg.org/simonrepp/faircamp>
- Tenda YunoHost: <https://apps.yunohost.org/app/faircamp>
- Informar dun problema: <https://github.com/YunoHost-Apps/faircamp_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing --debug
ou
sudo yunohost app upgrade faircamp -u https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
