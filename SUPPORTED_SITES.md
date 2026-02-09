# Supported Sites

NekoBox supports downloading from popular image boards and galleries through a combination of **Native High-Performance Scrapers** and integration with **gallery-dl**.

## 🚀 Native Support
These sites have built-in, optimized scrapers within NekoBox, offering the best performance, advanced filtering, and deep integration (e.g., login support, tag search).

| Site | URL | Features | Authentication |
|------|-----|----------|----------------|
| **Pixiv** | https://www.pixiv.net/ | User Gallery, Bookmarks, Rankings, Recommended, Search | Required (Cookie) |
| **Rule34** | https://rule34.xxx/ | Post Search, Tag Search, Pools | Optional |

---

## 🔌 Extended Support (via Gallery-dl)
NekoBox integrates with [gallery-dl](https://github.com/mikf/gallery-dl) to support additional popular image boards and galleries.

### Popular Image Boards & Galleries

| Site | URL | Category | Authentication |
|------|-----|----------|----------------|
| **Pixiv** | https://pixiv.net/ | Art Platform | Supported |
| **Reddit** | https://reddit.com/ | Social Media | Optional |
| **DeviantArt** | https://deviantart.com/ | Art Platform | OAuth |
| **ArtStation** | https://artstation.com/ | Art Platform | None |
| **Danbooru** | https://danbooru.donmai.us/ | Booru | Optional |
| **Gelbooru** | https://gelbooru.com/ | Booru | None |
| **Safebooru** | https://safebooru.org/ | Booru | None |
| **Konachan** | https://konachan.com/ | Booru | None |
| **Yande.re** | https://yande.re/ | Booru | None |
| **E-Hentai** | https://e-hentai.org/ | Gallery | Supported |
| **ExHentai** | https://exhentai.org/ | Gallery | Supported |
| **nhentai** | https://nhentai.net/ | Gallery | None |
| **Hitomi.la** | https://hitomi.la/ | Gallery | None |
| **4chan** | https://4chan.org/ | Imageboard | None |
| **8chan** | https://8chan.moe/ | Imageboard | None |
| **Imgur** | https://imgur.com/ | Image Hosting | None |
| **Flickr** | https://flickr.com/ | Photo Platform | OAuth |
| **Tumblr** | https://tumblr.com/ | Blogging Platform | Optional |
| **Newgrounds** | https://newgrounds.com/ | Art Platform | Supported |
| **Fur Affinity** | https://furaffinity.net/ | Art Platform | Cookies |
| **Inkbunny** | https://inkbunny.net/ | Art Platform | Supported |
| **Kemono** | https://kemono.cr/ | Archive Platform | Supported |
| **Coomer** | https://coomer.st/ | Archive Platform | Supported |
| **Bluesky** | https://bsky.app/ | Social Media | Supported |
| **Mastodon** | Various instances | Social Media | Optional |

> **Note**: This list shows popular sites. Gallery-dl supports 1000+ total sites. See [gallery-dl documentation](https://github.com/mikf/gallery-dl/blob/master/docs/supportedsites.md) for the complete list.

---

## Authentication Notes
- **None**: No authentication required
- **Optional**: Works without login, but may have limitations
- **Cookies**: Requires browser cookies export
- **OAuth**: Requires OAuth authentication
- **Supported**: Login supported through the application
- **Required**: Authentication mandatory to access content
