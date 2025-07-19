# mapshots

> QuakeWorld Map Screenshots

Used on various QuakeWorld websites, for example [QuakeWorld Hub](https://hub.quakeworld.nu).

## Usage

The mapshots are available via a AWS Cloudfront instance @ `https://a.quake.world/maphots/`

```html
<img src="https://a.quake.world/mapshots/webp/sm/ztndm3.webp" />
<img src="https://a.quake.world/mapshots/webp/lg/ztndm3.webp" />
```
lg = `1280x720`, sm = `640x360`

## Source

These mapshots were created using [automapshot-fte](https://github.com/vikpe/automapshot-fte) with the following settings:

- Camera position/angles from [settings/maps.json](./settings/maps.json).
- Textures from [Quake Retexturing Project](http://qrp.quakeone.com/).
