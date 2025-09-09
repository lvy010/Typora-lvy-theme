# MyGo-Anon Typora Macaroon Pink Theme

[中文](Anon-README.md)

> A macaroon pink Typora theme inspired by Anon from MyGo!!!!!

## Features

- 🎨 **Macaroon Pink Palette**: Soft macaroon pink tones as the main color scheme
- 🖼️ **Background Image**: Integrated Anon character image from MyGo!!!!!
- 💫 **Modern Design**: Semi-transparent effects and blur background
- 📝 **Elegant Typography**: Clear text hierarchy and comfortable reading experience
- 🌸 **Detail Optimization**: Custom scrollbars, selection effects, and more
- 🌈 **Light Theme**: Bright theme perfect for daytime use

## Installation

1. **Download Theme Files**
   - Download `mygo-anon.css` to your local machine
   - Ensure `mygo/png/anon.png` image file is in the correct relative path

2. **Install to Typora**
   - Open Typora
   - Go to **File** → **Preferences** → **Appearance**
   - Click **Open Theme Folder**
   - Copy `mygo-anon.css` and `mygo` folder to the theme folder

3. **Apply Theme**
   - Restart Typora
   - Go to **Themes** → **Mygo Anon**

## Theme Preview

### Main Features

- **Header Styles**: Macaroon pink headers, centered H1 with underline, H2 with left border
- **Link Styles**: Macaroon pink links with underline effects
- **Code Blocks**: Macaroon pink syntax highlighting with semi-transparent background
- **Quote Blocks**: Macaroon pink left border with light pink background
- **Task Lists**: Macaroon pink checkboxes
- **Tables**: Macaroon pink header background
- **Background**: Anon character image, fixed at bottom right with white base

### Macaroon Pink Configuration

```css
:root {
    --title-color: #f8a5c2;         /* Macaroon pink titles */
    --link-color: #f7b2d3;          /* Macaroon pink links */
    --code-color: #f8a5c2;          /* Macaroon pink code */
    --shadow-color: #fdf2f8;        /* Lighter macaroon pink shadow */
    --border: #f5d2e7;              /* Light macaroon pink border */
    --inline-code-bg: #fdf2f8;      /* Light macaroon pink code background */
}
```

## Customization

To adjust theme colors or styles, edit the `:root` variables section in `mygo-anon.css`.

### Change Background Image

To use a different background image, modify this CSS rule:

```css
body {
    background-image: url('./png/your-image.png');
}
```

### Adjust Transparency

You can adjust the content area transparency by modifying:

```css
#write {
    background-color: rgba(255, 255, 255, 0.9); /* Adjust the last value */
}
```

## Compatibility

- ✅ Windows
- ✅ macOS  
- ✅ Linux
- ✅ PDF Export (automatically hides background image)
- ✅ Print Mode
- ✅ Light mode optimized

## License

MIT License

## Changelog

### v2.0.0 (2025-01-20)
- 🎨 Upgraded to macaroon pink color palette
- 💫 Improved color harmony for better comfort
- 🌸 Enhanced readability and visual effects

### v1.0.0 (2025-09-09)
- 🎉 Initial release
- 🎨 Pink theme color scheme
- 🖼️ Integrated MyGo Anon background image
- 💫 Semi-transparent effects and modern design
- 📝 Complete Markdown syntax support

---

**MyGo!!!!!** is an anime about a girls' band, and Anon is one of the important characters. This theme pays tribute to this excellent work! 🎸✨
