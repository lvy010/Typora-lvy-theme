# MyGo-Anon Typora Pink Theme

[中文](README.md)

> A pink Typora theme inspired by Anon from MyGo!!!!!

## Features

- 🎨 **Pink Color Palette**: Warm pink tones as the main color scheme
- 🖼️ **Background Image**: Integrated Anon character image from MyGo!!!!!
- 💫 **Modern Design**: Semi-transparent effects and blur background
- 📝 **Elegant Typography**: Clear text hierarchy and comfortable reading experience
- 🌸 **Detail Optimization**: Custom scrollbars, selection effects, and more

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

- **Header Styles**: Pink headers, centered H1 with underline, H2 with left border
- **Link Styles**: Pink links with underline effects
- **Code Blocks**: Pink syntax highlighting with semi-transparent background
- **Quote Blocks**: Pink left border with light pink background
- **Task Lists**: Pink checkboxes
- **Tables**: Pink header background
- **Background**: Anon character image, fixed at bottom right

### Color Configuration

```css
:root {
    --title-color: #e91e63;      /* Pink titles */
    --link-color: #ff4081;       /* Pink links */
    --code-color: #e91e63;       /* Pink code */
    --shadow-color: #fce4ec;     /* Light pink shadow */
    --border: #f8bbd9;           /* Light pink border */
}
```

## Customization

To adjust theme colors or styles, edit the `:root` variables section in `mygo-anon.css`.

### Change Background Image

To use a different background image, modify this CSS rule:

```css
body {
    background-image: url('./mygo/png/your-image.png');
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

## License

MIT License

## Changelog

### v1.0.0 (2025-09-09)
- 🎉 Initial release
- 🎨 Pink theme color scheme
- 🖼️ Integrated MyGo Anon background image
- 💫 Semi-transparent effects and modern design
- 📝 Complete Markdown syntax support

---

**MyGo!!!!!** is an anime about a girls' band, and Anon is one of the important characters. This theme pays tribute to this excellent work! 🎸✨
