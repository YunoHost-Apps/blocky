<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Blocky YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/blocky)](https://ci-apps.yunohost.org/ci/apps/blocky/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/blocky)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/blocky)

[![Instalatu Blocky YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=blocky)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Blocky YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Blocky is a DNS proxy and ad-blocker for the local network written in Go.

**Paketatutako bertsioa:** 0.24~ynh1

## Pantaila-argazkiak

![Blocky(r)en pantaila-argazkia](./doc/screenshots/example.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://0xerr0r.github.io/blocky/latest/>
- Administratzaileen dokumentazio ofiziala: <https://0xerr0r.github.io/blocky/latest/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/0xERR0R/blocky>
- YunoHost Denda: <https://apps.yunohost.org/app/blocky>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/blocky_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/blocky_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/blocky_ynh/tree/testing --debug
edo
sudo yunohost app upgrade blocky -u https://github.com/YunoHost-Apps/blocky_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
