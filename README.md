# ShortsMaker

**Turn text into TikTok/Reels-style videos. No editing skills required.**

Write a script, pick a voice, add backgrounds — the app handles TTS, synced subtitles, transitions, and export.

## How It Works

### 1. Write Your Script
Type your voiceover text. Or describe your video idea and let AI generate a complete scenario with scenes, text, and overlay suggestions.

### 2. Pick a Voice
Choose from Edge TTS (free, 100+ voices) or ElevenLabs (realistic AI voices). The app generates audio with word-level timing for perfect subtitle sync.

### 3. Add Visuals
Select background images or videos. The app applies Ken Burns effects, slow zoom, pan, and other animations automatically.

### 4. Style Your Subtitles
Karaoke-style highlighting, typewriter effect, bounce, wave — pick a style that fits your content. Colors, fonts, and positioning are fully customizable.

### 5. Export
Hit render. Get an MP4 ready for upload.

## Features

- Scene transitions (fade, slide, zoom, wipe, glitch, cube, gradient)
- Subtitle animation styles
- Background animations (Ken Burns, drift, shake, pulse)
- Text overlays with entrance/exit animations
- Background music with automatic ducking
- Multi-scenario workflow for A/B testing
- Real-time 60fps preview

## Aspect Ratios

- 9:16 — TikTok, Shorts, Reels
- 16:9 — YouTube
- 1:1 — Instagram feed
- 4:5 — Instagram portrait

## Working Directories

On first launch, ShortsMaker creates its working folder at `~/Documents/ShortsMaker/`:

```
ShortsMaker/
├── assets/
│   ├── backgrounds/  # Images and videos for scenes
│   ├── overlays/     # Logos, stickers, watermarks
│   └── audio/        # Background music
└── temp/             # Cache and temporary files
```

You can change the location in Settings → Directories.

## Download

**[Releases](https://github.com/levskiy0/ShortsMaker/releases/)** — macOS, Windows, Linux

Free. No account. No watermarks.

---

GitHub: [github.com/levskiy0/ShortsMaker](https://github.com/levskiy0/ShortsMaker)

---

*Built because I needed it. Sharing because others might too.
