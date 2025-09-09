# MyGo-Mortis Typora Macaroon Green Dark Theme

[中文](Mortis-README.md)

> A macaroon green dark Typora theme inspired by Mortis from MyGo!!!!!

## Features

- 🌿 **Macaroon Green Palette**: Soft macaroon green tones as the main color scheme
- 🖼️ **Dark Background Image**: Integrated Mortis character image from MyGo!!!!!
- 🌙 **Dark Design**: Dark background with semi-transparent effects and blur
- 📝 **Eye-friendly Typography**: White/light green text optimized for night reading
- 🌲 **Detail Optimization**: Custom dark scrollbars, selection effects, and more
- 🌌 **Dark Theme**: Optimized dark theme perfect for nighttime use

## Installation

1. **Download Theme Files**
   - Download `mygo-Mortis.css` to your local machine
   - Ensure `mygo/png/Mortis.png` image file is in the correct relative path

2. **Install to Typora**
   - Open Typora
   - Go to **File** → **Preferences** → **Appearance**
   - Click **Open Theme Folder**
   - Copy `mygo-Mortis.css` and `mygo` folder to the theme folder

3. **Apply Theme**
   - Restart Typora
   - Go to **Themes** → **Mygo Mortis**

## Theme Preview

### Main Features

- **Header Styles**: Macaroon green headers with text shadow for enhanced readability
- **Link Styles**: Macaroon green links with underline effects
- **Code Blocks**: Macaroon green syntax highlighting with dark semi-transparent background
- **Quote Blocks**: Macaroon green left border with dark semi-transparent background
- **Task Lists**: Macaroon green checkboxes adapted for dark background
- **Tables**: Macaroon green header background with dark table styling
- **Background**: Mortis character image, fixed at bottom right with dark base
- **Text**: Light green-white text, clearly readable on dark background

### Macaroon Green Dark Configuration

```css
:root {
    --title-color: #a8e6a3;         /* Macaroon green titles */
    --text-color: #e8f5e8;          /* Light green-white text */
    --light-text-color: #c8e6c8;    /* Light green text */
    --link-color: #b8f5b8;          /* Macaroon green links */
    --code-color: #a8e6a3;          /* Macaroon green code */
    --shadow-color: rgba(168, 230, 163, 0.15); /* Macaroon green shadow */
    --border: rgba(168, 230, 163, 0.3);        /* Macaroon green border */
    --inline-code-bg: rgba(168, 230, 163, 0.2); /* Macaroon green code background */
}
```

### Dark Background Optimization

```css
body {
    background-color: #1a1a1a;      /* Dark background base */
}

#write {
    background-color: rgba(20, 30, 20, 0.85); /* Dark green semi-transparent background */
    backdrop-filter: blur(3px);     /* Background blur effect */
}
```

## Customization

To adjust theme colors or styles, edit the `:root` variables section in `mygo-Mortis.css`.

### Change Background Image

To use a different background image, modify this CSS rule:

```css
body {
    background-image: url('./png/your-image.png');
}
```

### Adjust Transparency and Readability

You can adjust the content area transparency by modifying:

```css
#write {
    background-color: rgba(20, 30, 20, 0.85); /* Adjust transparency */
    backdrop-filter: blur(3px);                /* Adjust blur level */
}
```

### Adjust Text Shadow

For better readability on dark background, you can adjust text shadow:

```css
h1, h2, h3, h4, h5, h6 {
    text-shadow: 0 1px 3px rgba(0, 0, 0, 0.5); /* Adjust shadow intensity */
}
```

## Compatibility

- ✅ Windows
- ✅ macOS  
- ✅ Linux
- ✅ PDF Export (automatically switches to light mode)
- ✅ Print Mode (automatically switches to light mode)
- ✅ Dark mode optimized
- ✅ Eye-friendly design

## License

MIT License

## Changelog

### v1.0.0 (2025-01-20)
- 🎉 Initial release
- 🌿 Macaroon green dark theme color scheme
- 🖼️ Integrated MyGo Mortis background image
- 🌙 Dark background with semi-transparent effects
- 📝 Text readability optimized for dark background
- 🌌 Complete dark mode support

---

**MyGo!!!!!** is an anime about a girls' band, and Mortis is one of the mysterious characters. This theme pays tribute to this excellent work! 🎸🌙
