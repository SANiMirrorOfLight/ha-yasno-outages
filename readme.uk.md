[![SWUbanner](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner-direct-single.svg)](https://stand-with-ukraine.pp.ua/)

![HA Yasno Outages Logo](./icons/logo.png)

# ⚡️ HA Yasno Outages

[![GitHub Release][gh-release-image]][gh-release-url]
[![GitHub Downloads][gh-downloads-image]][gh-downloads-url]
[![hacs][hacs-image]][hacs-url]
[![GitHub Sponsors][gh-sponsors-image]][gh-sponsors-url]
[![Patreon][patreon-image]][patreon-url]
[![Buy Me A Coffee][buymeacoffee-image]][buymeacoffee-url]
[![Twitter][twitter-image]][twitter-url]

> Інтеграція для графіків відключень електроенергії від [Yasno][yasno].

Ця інтеграція надає інформацію про графіки відключень електроенергії від [Yasno][yasno]: календар запланованих відключень, датчики часу для наступних запланованих відключень, тощо.

Це форк репозиторію https://github.com/denysdovhan/ha-yasno-outages, створений для виправлення календаря 5тої черги міста Дніпро

**💡 Примітка:** Цей проєкт не має жодного відношення до [Yasno][yasno]. Ця інтеграція розроблена ентузіастом. Інформація може відрізнятися від інфомації на офіційному сайті.

## Встановлення

Найшвидший спосіб встановити цю інтеграцію через [HACS][hacs-url], натиснувши кнопку нижче:

[![Add to HACS via My Home Assistant][hacs-install-image]][hasc-install-url]

Якщо це не працює, додайте цей репозиторій в HACS вручну, додавши цей URL:

1. Відвідайте **HACS** → **Інтеграції** → **...** (вгорі праворуч) → **Користувацькі репозиторії**
1. Натисніть **Додати**
1. Вставте `https://github.com/SANiMirrorOfLight/ha-yasno-outages` у поле **URL**
1. Виберіть **Інтеграція** як **Категорію**
1. **Yasno Outages** з'явиться у списку доступних інтеграцій. Встановіть її звичайним способом.

## Використання

Ця інтеграція налаштовується через інтерфейс користувача. На сторінці **Пристрої та сервіси** натисніть **Додати інтеграцію** і знайдіть **Yasno Відключення**.

Знайдіть свою групу, відвідавши вебсайт [Yasno][yasno] і введіть свою адресу в пошуковий рядок. Виберіть свою групу в конфігурації.

![Configuration flow](https://github.com/SANiMirrorOfLight/ha-yasno-outages/assets/3459374/e8bfde50-fcbe-45c3-b448-b451b0ac3bcd)

Потім ви можете додати інтеграцію на свою панель і бачити інформацію про наступні заплановані відключення.

![Device page](https://github.com/SANiMirrorOfLight/ha-yasno-outages/assets/3459374/df628647-fd2a-455d-9d08-0d1542b67e41)

Інтеграція також надає календар запланованих відключень. Ви можете використати [Картку календаря][calendar-card], щоб додати його на свою інформаційну панель.

![Calendar view](https://github.com/SANiMirrorOfLight/ha-yasno-outages/assets/3459374/b09c4db3-d0a0-4e06-8dd9-3f4a59f1d63e)

Ось приклад інформаційної панелі використовуючи цю інтеграцію:

![Dashboard example](https://github.com/SANiMirrorOfLight/ha-yasno-outages/assets/3459374/26c75595-8984-4a9f-893a-e4b6d838b7f2)

[gh-release-url]: https://github.com/SANiMirrorOfLight/ha-yasno-outages/releases/latest
[gh-release-image]: https://img.shields.io/github/v/release/SANiMirrorOfLight/ha-yasno-outages?style=flat-square
[gh-downloads-url]: https://github.com/SANiMirrorOfLight/ha-yasno-outages/releases
[gh-downloads-image]: https://img.shields.io/github/downloads/SANiMirrorOfLight/ha-yasno-outages/total?style=flat-square
[hacs-url]: https://github.com/hacs/integration
[hacs-image]: https://img.shields.io/badge/hacs-default-orange.svg?style=flat-square

<!-- References -->

[yasno]: https://yasno.com.ua/
[home-assistant]: https://www.home-assistant.io/
[calendar-card]: https://www.home-assistant.io/dashboards/calendar/
