# bskyeen

**Embed Bluesky videos, GIFs and images on Discord.**

Forked from [FerroEduardo/bskye](https://github.com/FerroEduardo/bskye), all credit goes to them!
I just modded it a bit to be funny and furry :3

///////

Written in TypeScript as a [Cloudflare Worker](https://workers.cloudflare.com/).

[![Production](https://github.com/FerroEduardo/bskye/actions/workflows/deploy-production.yaml/badge.svg)](https://github.com/FerroEduardo/bskye/actions/workflows/deploy-production.yaml)
[![Test](https://github.com/FerroEduardo/bskye/actions/workflows/test.yaml/badge.svg)](https://github.com/FerroEduardo/bskye/actions/workflows/test.yaml)

----

## Add `en` after `bsky` to make it `bskyeen.app`

## Embed Videos

![Video Embed Example](/.docs/embed-example/video.png)

## Embed GIFs

![GIF Embed Example](/.docs/embed-example/gif.png)

## Embed Images

![Single Image Embed Example](/.docs/embed-example/single-image.png)
![Multiple Images Embed Example](/.docs/embed-example/multiple-images.png)

## Embed Quotes

![Profile Embed Example](/.docs/embed-example/quote.png)

## Direct media links

To access media directly, simply prepend `d.` to the domain (`d.bskyeen.app`):

![Direct media links](/.docs/embed-example/direct-video.png)

> [!NOTE]  
> GIF animations are not properly supported due to Discord's limitations. When accessed directly, GIFs will display as static images rather than animated content.

### Gallery

Additionally, you can target specific media items within a post by appending an index number (starting from 1) to the URL:

> `https://d.bskyeen.app/profile/pfrazee.com/post/3lech75aa7k2f/4`

![Direct media links](/.docs/embed-example/gallery.png)

## Embed Profiles

![Profile Embed Example](/.docs/embed-example/profile.png)

## Disclaimer

While bskyeen supports Discord, full functionality for WhatsApp and Telegram may be limited.