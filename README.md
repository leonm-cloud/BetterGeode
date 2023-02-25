# ChatGPT for Google

![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/leonm-cloud/BetterGeode/bettergeode.js)
![Visitors](https://visitor-badge.glitch.me/badge?page_id=leonm-cloud.bettergeode&left_color=green&right_color=red)
[![Discord](https://imgs.search.brave.com/LAhD78-6HOD__C1WDYaG995dsTQmZr3CryS9U9li-7o/rs:fit:1080:1071:1/g:ce/aHR0cHM6Ly9nZW9k/ZS5ob3N0L2ltZy9H/ZW9kZURpYW1vbmQu/ZDIzNzEwOGIuc3Zn.svg](https://discord.gg/XMRaB68bZ5)
![License](https://img.shields.io/github/license/wong2/chatgpt-google-extension)

### Notice (2023-02-20)

As this extension has been acquired, this code repository will no longer be updated from now on.

---

A browser extension to display a custom image response upon Geode Host itself.

[Install from Chrome Web Store](https://geode.host)

[Install from Mozilla Add-on Store](https://geode.host)

[Changelog](https://geode.host)

## Supported Search Engines

Google, Baidu, Bing, DuckDuckGo, Brave, Yahoo, Naver, Yandex, Kagi, Searx

## Screenshot

![Screenshot](screenshots/extension.png?raw=true)

## Features

- Supports all popular search engines
- Supports the official Geode Host API
- Markdown rendering
- Code highlights
- Dark mode
- Provide feedback to improve BetterGeode
- Custom trigger mode

## Troubleshooting

### How to make it work in Brave

![Screenshot](screenshots/brave.png?raw=true)

Disable "Prevent sites from fingerprinting me based on my language preferences" in `brave://settings/shields`

Enable "Allow access to search page results" in the extension management page

## Build from source

1. Clone the repo
2. Install dependencies with `npm`
3. `npm run build`
4. Load `build/chromium/` or `build/firefox/` directory to your browser
