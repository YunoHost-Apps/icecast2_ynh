<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Icecast2 YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/icecast2.svg)](https://ci-apps.yunohost.org/ci/apps/icecast2/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/icecast2.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/icecast2.maintain.svg)

[![Instalatu Icecast2 YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=icecast2)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Icecast2 YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Icecast is a streaming media (audio/video) server which currently supports Ogg (Vorbis and Theora), Opus, WebM and MP3 streams.
It can be used to create an Internet radio station or a privately running jukebox and many things in between. It is very versatile in that new formats can be added relatively easily and supports open standards for communication and interaction.


**Paketatutako bertsioa:** 2.4.4~ynh1

## Pantaila-argazkiak

![Icecast2(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://icecast.org/>
- Administratzaileen dokumentazio ofiziala: <https://icecast.org/docs/>
- Jatorrizko aplikazioaren kode-gordailua: <https://gitlab.xiph.org/xiph/icecast-server>
- YunoHost Denda: <https://apps.yunohost.org/app/icecast2>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/icecast2_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/icecast2_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/icecast2_ynh/tree/testing --debug
edo
sudo yunohost app upgrade icecast2 -u https://github.com/YunoHost-Apps/icecast2_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
