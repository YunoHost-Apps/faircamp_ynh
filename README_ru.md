<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Faircamp для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/faircamp.svg)](https://ci-apps.yunohost.org/ci/apps/faircamp/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/faircamp.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/faircamp.maintain.svg)

[![Установите Faircamp с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=faircamp)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Faircamp быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Faircamp is a [Static Site Generator](https://en.wikipedia.org/wiki/Static_site_generator) dedicated to music producers.

With this package, Faircamp will automatically regenerate ([using Systemd Path Units](https://www.putorius.net/systemd-path-units.html)) your website if any change is made to your sources.

Alternatively to this package, you can [install Faircamp on your computer](https://simonrepp.com/faircamp/manual/installation.html) and use its rsync feature (ith the `--deploy` or `--deploy-destination` options) to send the builded website to a [My Webapp](https://apps.yunohost.org/app/my_webapp) folder on your YunoHost server.


**Поставляемая версия:** 0.16.0~ynh1

## Снимки экрана

![Снимок экрана Faircamp](./doc/screenshots/faircamp-screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://simonrepp.com/faircamp/>
- Официальная документация администратора: <https://simonrepp.com/faircamp/manual/>
- Репозиторий кода главной ветки приложения: <https://codeberg.org/simonrepp/faircamp>
- Магазин YunoHost: <https://apps.yunohost.org/app/faircamp>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/faircamp_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing --debug
или
sudo yunohost app upgrade faircamp -u https://github.com/YunoHost-Apps/faircamp_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
