# Sprite Forge - Animation Studio

A powerful, browser-based sprite animation tool for game developers. Upload sprite sheets or individual frames to preview, edit, and export your game animations.

![Sprite Forge Preview](preview.png)

## 🎮 Features

### Upload Options
- **Sprite Sheet Upload**: Upload a complete sprite sheet and extract individual frames
- **Individual Frames**: Upload multiple frame images to create animations
- **Drag & Drop**: Easy drag and drop support for all uploads

### Animation Controls
- **Play/Pause**: Preview your animation in real-time
- **Frame Navigation**: Step through frames one at a time
- **Speed Control**: Adjust FPS from 1-60
- **Loop Mode**: Toggle continuous playback
- **Ping-Pong**: Animation plays forward then backward
- **Reverse**: Play animation in reverse order
- **Frame Range**: Select specific frame ranges for sub-animations

### Editing Features
- **Delete Frames**: Remove unwanted frames
- **Reorder Frames**: Organize your animation sequence
- **Zoom**: Scale preview from 50% to 400%
- **Background Options**: Checkerboard, solid colors, or custom

### Animation Sequences
- Create multiple named sequences (Walk, Run, Jump, Attack, etc.)
- Each sequence has its own frame range, FPS, and loop settings
- Quickly switch between sequences

### Export Options
- **PNG Sprite Sheet**: Export as a combined sprite sheet
- **Individual Frames**: Download each frame separately
- **Configurable Columns**: Set sprite sheet layout
- **Scale Options**: Export at 1x, 2x, or 4x resolution

## 🚀 Live Demo

Visit: `https://[your-username].github.io/sprite-forge/`

## 💻 Local Usage

1. Clone or download this repository
2. Open `index.html` in your web browser
3. No server or build process required!

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Play/Pause |
| `←` | Previous Frame |
| `→` | Next Frame |
| `Home` | First Frame |
| `End` | Last Frame |

## 📁 Hosting on GitHub Pages

1. Fork or clone this repository
2. Go to repository **Settings** → **Pages**
3. Set source to **main branch** and **/ (root)**
4. Your site will be live at `https://[username].github.io/[repo-name]/`

## 🎨 Supported Formats

**Input:**
- PNG (recommended for transparency)
- JPG/JPEG
- GIF (static)
- WebP

**Output:**
- PNG Sprite Sheet
- Individual PNG frames

## 📐 Sprite Sheet Configuration

When uploading a sprite sheet, configure:
- **Columns**: Number of frames per row
- **Rows**: Number of rows in the sheet
- **Frame Width/Height**: Auto-detected or manual input

## 🛠️ Technical Details

- Pure HTML/CSS/JavaScript - no dependencies
- Works offline after initial load
- Pixel-perfect rendering with `image-rendering: pixelated`
- Canvas-based frame extraction and export

## 📝 License

MIT License - Feel free to use in personal and commercial projects.

## 🤝 Contributing

Contributions welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests

---

Made with ❤️ for game developers
