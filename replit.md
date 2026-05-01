# David Cyril Portfolio — davidcyril.name.ng

## Overview
A fully rebuilt personal portfolio site for David Cyril. Static site served via Python `http.server` on port 5000.

## Tech Stack
- Pure HTML, CSS, Vanilla JavaScript (static site)
- Python http.server for serving (port 5000, bound to 0.0.0.0)
- No build step required

## Structure
```
/
├── index.html          — Portfolio homepage (hero, about, 40+ projects grid, services, contact)
├── css/shared.css      — Design system: dark theme, gold accent (#FFD700), shared components
├── <project>/          — 44 project directories, each with index.html
└── projects/           — Old project directory (unused)
```

## API Base
All dynamic projects use: `https://apis.davidcyril.name.ng`

Available endpoints:
- `/deepseek-v3` — AI chat (DeepSeek)
- `/gemini` — AI chat (Gemini)
- `/ytmp4`, `/ytmp3` — YouTube downloader
- `/tiktok` — TikTok downloader
- `/facebook` — Facebook downloader
- `/spotifydl` — Spotify downloader
- `/aio` — All-in-one social downloader
- `/apk` — APK downloader
- `/instagram` — Instagram downloader
- `/twitter` — Twitter/X downloader
- `/pinterest` — Pinterest downloader
- `/lyrics` — Song lyrics
- `/weather` — Weather data
- `/random/quotes` — Random quotes
- `/removebg` — Background removal
- `/temp-mail` — Temp mail
- `/search/wallpaper` — Wallpaper search
- ImgBB key (for uploads): `1fe5c36a643f15d1e5478c716f876a4c`

## All Project Pages (44 total)
| Page | Type | Description |
|------|------|-------------|
| chatbot | API | AI chatbot (DeepSeek + Gemini) |
| gemini | API | Gemini AI chat |
| youtube | API | YouTube MP4/MP3 downloader |
| tiktok | API | TikTok video downloader |
| facebook | API | Facebook video downloader |
| spotify | API | Spotify track downloader |
| instagram | API | Instagram downloader |
| twitter | API | Twitter/X downloader |
| pinterest | API | Pinterest downloader |
| aio | API | All-in-one social downloader |
| apk | API | APK downloader |
| weather | API | Weather app |
| quotes | API | Random quotes |
| tempmail | API | Temporary email |
| removebg | API | Background remover |
| remini | API | Image enhancer |
| wallpaper | API | Wallpaper search |
| lyrics | API | Song lyrics finder |
| calculator | Tool | Scientific calculator |
| password | Tool | Password generator |
| bmi | Tool | BMI calculator |
| age | Tool | Age calculator |
| colorpicker | Tool | Color picker + palette |
| wordcount | Tool | Word/character counter |
| base64 | Tool | Base64 encoder/decoder |
| json | Tool | JSON formatter/validator |
| pomodoro | Tool | Pomodoro timer |
| todo | Tool | Todo list (localStorage) |
| notes | Tool | Notes app (localStorage) |
| stopwatch | Tool | Stopwatch + countdown timer |
| typing | Tool | Typing speed test |
| qrcode | Tool | QR code generator |
| morse | Tool | Morse code translator + audio |
| unit | Tool | Unit converter (8 categories) |
| gradient | Tool | CSS gradient generator |
| tip | Tool | Tip calculator + bill splitter |
| binary | Tool | Number base converter |
| loan | Tool | Loan calculator + amortization |
| random | Tool | Random generator (8 types) |
| regex | Tool | Regex tester |
| markdown | Tool | Markdown editor (live preview) |
| invoice | Tool | Invoice generator (PDF print) |
| obfuscator | Tool | JavaScript obfuscator |

## External Links (in homepage, no internal page)
- **TikSave** → https://tiksave.name.ng
- **Cinverse** → https://cinverse.com.ng

## Design System (css/shared.css)
- Background: `#0a0a0a` / `#111`
- Card bg: `#1a1a1a` / `#161616`
- Accent: `#FFD700` (gold)
- Success: `#2ed573`, Danger: `#ff4757`
- Border radius: `12px`, Font: system-ui

## Personal Info
- Photo: `https://files.catbox.moe/4hq1u5.jpg`
- WhatsApp: `+2349066528353`
- Email: `Davidcyril209@gmail.com`

## Workflow
- Name: "Start application"
- Command: `python3 -m http.server 5000 --bind 0.0.0.0`
- Port: 5000
