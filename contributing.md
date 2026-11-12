
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=11,25,0&height=240&section=header&text=AllManga%20API&fontSize=68&fontColor=ffffff&animation=scaleIn&fontAlignY=45&desc=The%20Ultimate%20Anime%20Streaming%20Engine&descAlignY=70&descSize=20" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Inter&size=20&duration=2500&pause=800&color=FFB703&center=true&vCenter=true&width=750&lines=High-Speed+Scraping.;Multi-Language+Subtitles.;Build+your+own+Anime+Platform." alt="Typing SVG"/>

<br/><br/>

<a href="https://share.google/H7nReu6didpZTpaSL">
  <img src="https://img.shields.io/badge/📚_READ_DOCS-FFB703?style=for-the-badge&logo=readthedocs&logoColor=black&labelColor=FB8500" height="50"/>
</a>
&nbsp;
<a href="https://share.google/H7nReu6didpZTpaSL">
  <img src="https://img.shields.io/badge/🚀_LIVE_API-023047?style=for-the-badge&logo=fastapi&logoColor=white&labelColor=8ECAE6" height="50"/>
</a>
&nbsp;
<a href="https://share.google/H7nReu6didpZTpaSL">
  <img src="https://img.shields.io/badge/📦_GET_SOURCE-219EBC?style=for-the-badge&logo=github&logoColor=white&labelColor=023047" height="50"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/version-2.8.0-023047?style=flat-square&logo=semanticrelease&logoColor=white"/>
<img src="https://img.shields.io/badge/Node.js-20+-219EBC?style=flat-square&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/license-MIT-8ECAE6?style=flat-square&logo=opensourceinitiative&logoColor=black"/>
<img src="https://img.shields.io/badge/downloads-59K%2B-FFB703?style=flat-square&logo=github&logoColor=black"/>
<img src="https://img.shields.io/badge/latency-<50ms-FB8500?style=flat-square&logo=speedtest&logoColor=white"/>

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌊 Stream Anime Without Limits

**Allmanga Anime Streaming API** is a robust, high-performance backend service designed to aggregate and serve anime content from multiple sources into a single, unified REST API. Built for developers, it eliminates the headache of writing custom scrapers for every anime site by providing a standardized JSON interface for metadata, episodes, and high-quality streaming links.

Whether you are building a native mobile app, a web-based anime portal, or a Discord bot, this API gives you **instant access to thousands of titles**, complete with multi-language subtitles and multiple resolution options. It handles the heavy lifting of parsing, caching, and proxy routing so you can focus on building a beautiful frontend.

> 💡 **Why build this API?** Because the anime streaming landscape is fragmented and highly volatile. AllManga acts as a shield, standardizing the data and keeping your application online even when source sites change their architecture.

<br/>

<table align="center" width="100%">
<tr>
<td align="center" width="25%">

### ⚡
**Lightning Fast**
Redis-powered caching ensures sub-50ms response times for metadata.

</td>
<td align="center" width="25%">

### 🛡️
**Bypass Protection**
Built-in bypasses for Cloudflare and DDoS-Guard on source platforms.

</td>
<td align="center" width="25%">

### 🗣️
**Multi-Sub**
Returns links for English, Spanish, Arabic, and native Japanese subs.

</td>
<td align="center" width="25%">

### 🧩
**RESTful Design**
Clean, predictable endpoints that are easy to integrate with any stack.

</td>
</tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ⚡ Why Developers Choose AllManga

<div align="center">

| 🧩 **The Challenge** | 💡 **Our Solution** | 📈 **The Result** |
|:---|:---|:---|
| Source sites constantly change HTML | **Modular scraper architecture** with auto-updates | Your app never breaks |
| M3U8 stream links expire quickly | **On-the-fly token generation** and proxy routing | Uninterrupted video playback |
| Slow scraping kills mobile apps | **Edge caching** and optimized queries | Blazing fast load times |
| Building scrapers takes months | **Ready-to-use JSON API** | Launch your anime app in days |

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 API Endpoints

<div align="center">

| Endpoint | Description | Example |
|:---|:---|:---|
| `/search?q=` | Search for anime by title | `/search?q=naruto` |
| `/anime/{id}` | Get detailed metadata (synopsis, genres, score) | `/anime/21` |
| `/episodes/{id}` | List all available episodes | `/episodes/21` |
| `/stream/{id}/{ep}` | Get M3U8 streaming links | `/stream/21/1` |
| `/trending` | Fetch currently trending anime globally | `/trending` |

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🖼️ API Response Preview

<div align="center">

<img width="1920" height="1080" alt="anime-streaming-rest-api-v0-lrdpz61q08de1" src="https://github.com/user-attachments/assets/e08fdab8-44db-451f-a1f7-adaf63b77e2e" />

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🚀 Quick Start

> **Three steps. Under five minutes. No credit card.**

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourname/allmanga-api.git
cd allmanga-api
```

### 2️⃣ Install and run with Docker

```bash
docker-compose up -d
```

### 3️⃣ Test the API

```bash
curl http://localhost:3000/trending
```

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ⌨️ Tech Stack & Architecture

<div align="center">

| Layer | Responsibility | Tech |
|:---|:---|:---|
| 🚦 **API Gateway** | Rate limiting, routing, and request validation | `Fastify` |
| 🕷️ **Scrapers** | Fetching and parsing data from sources | `Cheerio` / `Puppeteer` |
| 🗄️ **Cache** | Storing frequently accessed metadata | `Redis` |
| 🎬 **Stream Proxy** | Fetching M3U8 playlists and proxying video chunks | `Node.js Streams` |

</div>

The system is built with a plugin-based architecture. You can easily add new anime sources by creating a new scraper module that implements the standard `SourceProvider` interface.

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧠 Pro Tips

<table align="center" width="100%">
<tr>
<td width="50%">

**For app developers**
- 🚀 Implement infinite scrolling using the `/search` pagination
- 🎨 Use the `cover_image` URLs directly in your frontend
- ⚡ Cache the `/anime/{id}` response locally for 24 hours
- 🎬 Use `HLS.js` for smooth M3U8 playback in web browsers

</td>
<td width="50%">

**For self-hosters**
- 🌐 Run behind Cloudflare to protect your API from abuse
- 🔒 Use API keys for production deployments
- 💾 Allocate at least 2GB of RAM for Redis caching
- 🔄 Schedule cron jobs to update the source modules

</td>
</tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ❓ Frequently Asked Questions

<details>
<summary><b>Does this API store or host any video files?</b></summary>

No. This API acts as a **scraper and proxy**. It aggregates streaming links (M3U8) from third-party providers and proxies the requests to bypass CORS restrictions. We do not host any copyrighted media on our servers.
</details>

<details>
<summary><b>Is there a rate limit?</b></summary>

The hosted public API has a rate limit of **60 requests per minute** per IP. If you self-host the project, you can configure the rate limit in the `config.json` file to suit your needs.
</details>

<details>
<summary><b>Can I use this for a commercial project?</b></summary>

The code is MIT licensed, so you can use it commercially. However, you are responsible for the content you stream. We highly recommend using official licensing for commercial anime streaming.
</details>

<details>
<summary><b>How often are the sources updated?</b></summary>

We maintain the scrapers weekly. If a source site drops a major update, we usually push a fix within 24-48 hours. Pull requests are always welcome.
</details>

<details>
<summary><b>How do I report a broken endpoint?</b></summary>

Open an issue on the GitHub repository with the specific anime ID and the endpoint you tested. Include the error message and the expected output.
</details>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

<br/>

<div align="center">

<a href="https://share.google/H7nReu6didpZTpaSL">
  <img src="https://img.shields.io/badge/🚀_EXPLORE_THE_API-FFB703?style=for-the-badge&logo=swagger&logoColor=black&labelColor=FB8500" height="55"/>
</a>

<br/><br/>

**⭐ If this API powered your project — star the repo!**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=11,25,0&height=140&section=footer&text=Stream.+Build.+Innovate.&fontSize=22&fontColor=FFB703" width="100%"/>

</div>

