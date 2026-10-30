<p align="center">
  <img src="assets/logo.png" alt="9bot logo" width="96">
</p>

<h1 align="center">9bot Wayback Archive</h1>

<p align="center">Automatic snapshots of <a href="https://9bot.com.br">9bot.com.br</a> on the Internet Archive Wayback Machine, twice a day.</p>

<p align="center">
  <a href="https://github.com/9-bot/wayback-archive/actions/workflows/wayback.yml"><img src="https://github.com/9-bot/wayback-archive/actions/workflows/wayback.yml/badge.svg" alt="Wayback Machine workflow status"></a>
  <a href="https://github.com/marketplace/actions/wayback-machine"><img src="https://img.shields.io/badge/Action-JamieMagee%2Fwayback%40v2-red?logo=githubactions&logoColor=white" alt="Action: JamieMagee/wayback@v2"></a>
  <a href="https://web.archive.org/web/*/9bot.com.br*"><img src="https://img.shields.io/badge/Wayback%20Machine-9bot.com.br-555?logo=internetarchive&logoColor=white" alt="Wayback Machine: 9bot.com.br"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue" alt="License: MIT"></a>
</p>

This repository keeps a public, timestamped history of the 9bot website. A GitHub Actions workflow asks the Wayback Machine to capture each language version of the home page twice a day, so every change to the site stays on record.

9bot is a paid product for managing WhatsApp groups, announcement groups, and channels, with a 7 day trial.

> 9bot is an independent company and is not affiliated with, endorsed by, or sponsored by Meta Platforms or WhatsApp. WhatsApp is a trademark of its owner.

## Archived pages

| Language | Page | History |
| --- | --- | --- |
| Português | [9bot.com.br/pt](https://9bot.com.br/pt) | [Snapshots](https://web.archive.org/web/*/https://9bot.com.br/pt*) |
| English | [9bot.com.br/en](https://9bot.com.br/en) | [Snapshots](https://web.archive.org/web/*/https://9bot.com.br/en*) |
| Español | [9bot.com.br/es](https://9bot.com.br/es) | [Snapshots](https://web.archive.org/web/*/https://9bot.com.br/es*) |
| 中文 | [9bot.com.br/zh](https://9bot.com.br/zh) | [Snapshots](https://web.archive.org/web/*/https://9bot.com.br/zh*) |

## Schedule

| Run | UTC | Brasília (UTC-3) |
| --- | --- | --- |
| Morning | 09:00 | 06:00 |
| Evening | 21:00 | 18:00 |

The workflow can also be started by hand from the [Actions tab](https://github.com/9-bot/wayback-archive/actions/workflows/wayback.yml) with **Run workflow**.

## How it works

1. GitHub Actions starts [`.github/workflows/wayback.yml`](.github/workflows/wayback.yml) on schedule.
2. The [Wayback Machine action](https://github.com/marketplace/actions/wayback-machine) sends each URL to the Save Page Now service.
3. The Internet Archive stores a new capture with a screenshot, and the run log shows the snapshot links.

## Links

- Website: [9bot.com.br](https://9bot.com.br)
- MCP server: [9-bot/mcp](https://github.com/9-bot/mcp)
- Contact: contato@9bot.com.br

## License

[MIT](LICENSE)
