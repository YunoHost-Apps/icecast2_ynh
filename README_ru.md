<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Icecast2 для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/icecast2)](https://ci-apps.yunohost.org/ci/apps/icecast2/)
![Состояние работы](https://apps.yunohost.org/badge/state/icecast2)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/icecast2)

[![Установите Icecast2 с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=icecast2)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Icecast2 быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Icecast is a streaming media (audio/video) server which currently supports Ogg (Vorbis and Theora), Opus, WebM and MP3 streams.
It can be used to create an Internet radio station or a privately running jukebox and many things in between. It is very versatile in that new formats can be added relatively easily and supports open standards for communication and interaction.


**Поставляемая версия:** 2.4.4~ynh1

## Снимки экрана

![Снимок экрана Icecast2](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://icecast.org/>
- Официальная документация администратора: <https://icecast.org/docs/>
- Репозиторий кода главной ветки приложения: <https://gitlab.xiph.org/xiph/icecast-server>
- Магазин YunoHost: <https://apps.yunohost.org/app/icecast2>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/icecast2_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/icecast2_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/icecast2_ynh/tree/testing --debug
или
sudo yunohost app upgrade icecast2 -u https://github.com/YunoHost-Apps/icecast2_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
