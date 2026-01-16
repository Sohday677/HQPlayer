# HQPlayer

A high-quality HTML local video player with a YouTube-like interface and experience.

## 🎬 Features

- **YouTube-like UI**: Beautiful, familiar video player interface inspired by YouTube
- **Local File Support**: Play any local video file by clicking or drag & drop
- **Ambient Lighting**: Dynamic ambient light effect that creates a glow around the video based on its colors
- **Full Keyboard Support**: All standard YouTube keyboard shortcuts work
- **Picture-in-Picture**: Watch videos in a floating window
- **Playback Speed Control**: Adjust playback speed from 0.25x to 2x
- **Fullscreen Mode**: Immersive fullscreen viewing experience
- **Progress Bar Preview**: Hover to see timestamps
- **Volume Controls**: Click or drag to adjust volume

## 🚀 Live Demo

Visit the live demo: [HQPlayer on GitHub Pages](https://sohday677.github.io/HQPlayer/)

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` / `K` | Play / Pause |
| `J` | Rewind 10 seconds |
| `L` | Forward 10 seconds |
| `←` | Rewind 5 seconds |
| `→` | Forward 5 seconds |
| `↑` | Volume up |
| `↓` | Volume down |
| `M` | Mute / Unmute |
| `F` | Toggle fullscreen |
| `I` | Toggle Picture-in-Picture |
| `0-9` | Seek to percentage |
| `<` | Decrease playback speed |
| `>` | Increase playback speed |

## 🎨 Ambient Mode

The ambient lighting feature creates a beautiful glow effect around the video player when there are black borders (letterboxing). The colors of the glow dynamically match the video content, creating an immersive viewing experience.

Toggle ambient mode on/off from the settings menu (gear icon).

## 📁 Supported Formats

HQPlayer supports all video formats that your browser supports, including:
- MP4 (H.264, H.265)
- WebM (VP8, VP9, AV1)
- OGG (Theora)
- MOV
- And more!

## 🛠️ Local Development

Simply open `index.html` in your browser, or serve it with a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

## 📝 License

MIT License - feel free to use this project for personal or commercial purposes.
