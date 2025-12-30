# ShortsMaker

**Create viral short-form videos in minutes, not hours.**

ShortsMaker is a desktop application that transforms your ideas into polished vertical videos ready for TikTok, YouTube Shorts, and Instagram Reels. No video editing experience required.

## What It Does

Write a script, pick a voice, choose your visuals — ShortsMaker handles the rest. The app automatically generates:

- **Text-to-Speech voiceover** with natural-sounding AI voices
- **Synced subtitles** that highlight words as they're spoken (karaoke-style, typewriter, and more)
- **Smooth transitions** between scenes (fades, slides, zooms, glitches)
- **Animated backgrounds** with Ken Burns effects, slow zoom, pan, and drift
- **Text overlays** with eye-catching animations (pop-in, fire reveal, glitch)

## Key Features

### AI-Powered Workflow
Describe your video idea in plain text and let AI generate complete scenarios — scenes, voiceover scripts, backgrounds, and overlay suggestions. Review, tweak, and render.

### Real-Time Preview
See your video come to life as you edit. ThreeJS-powered renderer delivers smooth 60fps playback with all effects applied.

### Multiple Scenarios
Work on several versions of the same video simultaneously. A/B test different scripts, voices, or visual styles before committing.

### Export Anywhere
Render to MP4, WebM, or MOV in resolutions from mobile-friendly to 4K. Background music with automatic ducking keeps your voiceover clear.

### Aspect Ratios for Every Platform
- 9:16 for TikTok, Shorts, Reels
- 16:9 for YouTube
- 1:1 for Instagram feed
- 4:5 for Instagram portrait
- And more

## Working Directories

On first launch, ShortsMaker creates its working folder at `~/Documents/ShortsMaker/` with the following structure:

```
ShortsMaker/
├── assets/           # Your media library
│   ├── backgrounds/  # Images and videos for scene backgrounds
│   ├── overlays/     # Images for overlay elements
│   ├── audio/        # Background music and sound effects
│   └── fonts/        # Custom font files (.ttf, .otf, .woff)
└── temp/             # Temporary files (cache, TTS, exports)
```

### Organizing Your Assets

**backgrounds/** — Drop your images (PNG, JPG, WebP) and videos (MP4, WebM, MOV) here. These appear in the background picker when editing scenes.

**overlays/** — Store images you want to place over your video — logos, stickers, watermarks, reaction images.

**audio/** — Background music tracks. ShortsMaker supports MP3, WAV, OGG, and M4A. The app automatically ducks music volume during voiceover.

**fonts/** — Custom fonts for subtitles and text overlays. After adding fonts here, restart the app to load them.

You can change the working directory location in Settings → Directories.

## The Mission

Professional video production tools are complex, expensive, and time-consuming. Short-form content demands speed. ShortsMaker bridges this gap — giving creators a focused tool that does one thing exceptionally well: turning ideas into scroll-stopping vertical videos.

Whether you're a content creator, marketer, educator, or just someone with a story to tell — your next viral short is just a few clicks away.

---

*Built with Electron, React, and a custom ThreeJS rendering engine.*
