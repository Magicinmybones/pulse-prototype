# pulse-prototype

Live site: [https://pulse-prototype.spaceedu-planet-earth.workers.dev](https://pulse-prototype.spaceedu-planet-earth.workers.dev)

Standalone static prototype from `pulse(2).html`.

The deployable site is in `site/`. Embedded images and fonts were extracted to `site/assets/`.

The opening sequence runs once on page load, keeps the portrait background still, skips itself for reduced-motion users, and clears its animation styles after 2.35 seconds.

## Deploy

```sh
npx wrangler deploy
```

## Extracted assets

- [`assets/fonts/font-1.woff2`](https://pulse-prototype.spaceedu-planet-earth.workers.dev/assets/fonts/font-1.woff2)
- [`assets/fonts/font-2.woff2`](https://pulse-prototype.spaceedu-planet-earth.workers.dev/assets/fonts/font-2.woff2)
- [`assets/images/image-1.jpg`](https://pulse-prototype.spaceedu-planet-earth.workers.dev/assets/images/image-1.jpg)
