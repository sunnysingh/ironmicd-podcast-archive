# IronMic'd Podcast Archive

A static archive site for the IronMic'd podcast.

Deployed to [podcast.ironmic.fm](https://podcast.ironmic.fm/) via [Cloudflare Pages](https://pages.cloudflare.com/).

Audio files are stored on `media.ironmic.fm` via [Cloudflare R2](https://developers.cloudflare.com/r2/).

<img src="./source/assets/podcast-art.png" width="250" height="250">

## Usage

Compile the site:

```sh
npm run build
```

To preview locally, use a static file server like [serve](https://www.npmjs.com/package/serve):

```sh
npx serve .build-output
```
