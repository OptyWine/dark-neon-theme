# Dark Neon Opty - Discord Theme

![Theme Preview](https://i.imgur.com/ocfzb8N.png)  
*A vibrant dark-neon theme for Discord with glowing accents*

## ✨ Features
- **Customizable Colors** - Change all accents via CSS variables
- **Dark Base** - Eye-friendly dark background
- **Neon Glow Effects** - Vibrant highlights for UI elements
- **Background Options** - Supports custom images with blur/brightness control
- **Collapsible UI** - Optional toggle for user list (enabled by default)

## ⚙️ Installation

### Via Vencord (Recommended):
1. Install [Vencord](https://github.com/Vencord/Vencord)
2. Place `DarkNeon-Opty.theme.css` in:
   - Windows: `%appdata%/Vencord/themes`
   - Linux/Mac: `~/.config/Vencord/themes`
3. Enable in Vencord Settings > Themes

### Manual CSS:
1. Discord Settings > Appearance > Themes
2. Enable "Developer Mode"
3. Paste the CSS into your client's custom CSS file

## 🎨 Customization
Modify these variables in the theme file:

```css
:root {
  /* Core Colors */
  --rgb-highlight: 214, 39, 39;   /* Main accent (buttons, links) */
  --rgb-background: 0, 0, 0;      /* Base background */
  --rgb-text: 197, 200, 198;      /* Primary text */
  
  /* Status Colors */
  --rgb-online-color: 57, 255, 20;
  --rgb-dnd-color: 255, 0, 0;
  
  /* Background Effects */
  --background-image: unset;      /* Use url() for custom image */
  --background-blur: 20px;        /* Adjust blur intensity */
}
```

## ❓ Support
- Report issues on [GitHub Issues](https://github.com/OptyWine/dark-neon-theme/issues)
