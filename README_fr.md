<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Icecast pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/icecast.svg)](https://ci-apps.yunohost.org/ci/apps/icecast/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/icecast.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/icecast.maintain.svg)

[![Installer Icecast avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=icecast)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Icecast rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Icecast est un serveur de streaming multimédia (audio/vidéo) qui prend actuellement en charge les flux Ogg (Vorbis et Theora), Opus, WebM et MP3.
Il peut être utilisé pour créer une station de radio Internet ou un jukebox privé et bien d'autres choses encore. Il est très polyvalent dans la mesure où de nouveaux formats peuvent être ajoutés relativement facilement et prend en charge les normes ouvertes de communication et d'interaction.

**Version incluse :** 2.4.4~ynh1

## Captures d’écran

![Capture d’écran de Icecast](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://icecast.org/>
- Documentation officielle de l’admin : <https://icecast.org/docs/>
- Dépôt de code officiel de l’app : <https://gitlab.xiph.org/xiph/icecast-server>
- YunoHost Store : <https://apps.yunohost.org/app/icecast>
- Signaler un bug : <https://github.com/YunoHost-Apps/icecast_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/icecast_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/icecast_ynh/tree/testing --debug
ou
sudo yunohost app upgrade icecast -u https://github.com/YunoHost-Apps/icecast_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
