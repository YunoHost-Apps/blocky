<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Blocky untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/blocky)](https://ci-apps.yunohost.org/ci/apps/blocky/)
![Status kerja](https://apps.yunohost.org/badge/state/blocky)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/blocky)

[![Pasang Blocky dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=blocky)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Blocky secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Blocky is a DNS proxy and ad-blocker for the local network written in Go.

**Versi terkirim:** 0.24~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Blocky](./doc/screenshots/example.jpg)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://0xerr0r.github.io/blocky/latest/>
- Dokumentasi admin resmi: <https://0xerr0r.github.io/blocky/latest/>
- Depot kode aplikasi hulu: <https://github.com/0xERR0R/blocky>
- Gudang YunoHost: <https://apps.yunohost.org/app/blocky>
- Laporkan bug: <https://github.com/YunoHost-Apps/blocky_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/blocky_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/blocky_ynh/tree/testing --debug
atau
sudo yunohost app upgrade blocky -u https://github.com/YunoHost-Apps/blocky_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
