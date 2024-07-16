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

> An integration for electricity outages plans by [Yasno][yasno].

This integration for [Home Assistant][home-assistant] provides information about electricity outages plans by [Yasno][yasno]: calendar of planned outages, time sensors for the next planned outages, and more.

This is a fork of the https://github.com/denysdovhan/ha-yasno-outages repository that was made to change the 5th queue calendar to match the Dnipro outage scheduler

[**🇺🇦 Читати документацію українською 🇺🇦**](./readme.uk.md)

**💡 Note:** This is not affiliated with [Yasno][yasno] in any way. This integration is developed by an individual. Information may vary from their official website.

## Installation

The quickest way to install this integration is via [HACS][hacs-url] by clicking the button below:

[![Add to HACS via My Home Assistant][hacs-install-image]][hasc-install-url]

If it doesn't work, adding this repository to HACS manually by adding this URL:

1. Visit **HACS** → **Integrations** → **...** (in the top right) → **Custom repositories**
1. Click **Add**
1. Paste `https://github.com/SANiMirrorOfLight/ha-yasno-outages` into the **URL** field
1. Chose **Integration** as a **Category**
1. **Yasno Outages** will appear in the list of available integrations. Install it normally.

## Usage

This integration is configurable via UI. On **Devices and Services** page, click **Add Integration** and search for **Yasno Outages**.

Find your group by visiting [Yasno][yasno] website and typing your address in the search bar. Select your group in the configuration.

![Configuration flow](https://github.com/SANiMirrorOfLight/ha-yasno-outages/assets/3459374/e8bfde50-fcbe-45c3-b448-b451b0ac3bcd)

Then you can add the integration to your dashboard and see the information about the next planned outages.

![Device page](https://github.com/SANiMirrorOfLight/ha-yasno-outages/assets/3459374/df628647-fd2a-455d-9d08-0d1542b67e41)

Integration also provides a calendar view of planned outages. You can add it to your dashboard as well via [Calendar card][calendar-card].

![Calendar view](https://github.com/SANiMirrorOfLight/ha-yasno-outages/assets/3459374/b09c4db3-d0a0-4e06-8dd9-3f4a59f1d63e)

Here's an example of a dashboard using this integration:

![Dashboard example](https://github.com/SANiMirrorOfLight/ha-yasno-outages/assets/3459374/26c75595-8984-4a9f-893a-e4b6d838b7f2)

<!-- Badges -->

[gh-release-url]: https://github.com/SANiMirrorOfLight/ha-yasno-outages/releases/latest
[gh-release-image]: https://img.shields.io/github/v/release/SANiMirrorOfLight/ha-yasno-outages?style=flat-square
[gh-downloads-url]: https://github.com/SANiMirrorOfLight/ha-yasno-outages/releases
[gh-downloads-image]: https://img.shields.io/github/downloads/SANiMirrorOfLight/ha-yasno-outages/total?style=flat-square
[hacs-url]: https://github.com/hacs/integration
[hacs-image]: https://img.shields.io/badge/hacs-default-orange.svg?style=flat-square

<!-- References -->

[yasno]: https://yasno.com.ua/
[home-assistant]: https://www.home-assistant.io/
[hacs-install-image]: https://my.home-assistant.io/badges/hacs_repository.svg
[calendar-card]: https://www.home-assistant.io/dashboards/calendar/
