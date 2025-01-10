# Animated Side Menu for WordPress Elementor

This repository contains the code and instructions for implementing an animated side menu on a WordPress website using Elementor. The menu features smooth animations, responsive design, and full customization options.

---

## Features
- **Smooth Animations**: Elegant transitions for menu interactions.
- **Responsive Design**: Works seamlessly across all device sizes.
- **Customizable**: Easily tweak styles and behavior to suit your website.

---

## Installation Steps

### 1. CSS Integration
1. Open your WordPress admin panel.
2. Navigate to **Appearance > Customize > Additional CSS**.
3. Copy the code from `assets/style.css` and paste it into the editor.
4. Publish the changes.

### 2. JavaScript Integration
Option 1: Using a plugin
1. Install a plugin like **Insert Headers and Footers**.
2. Paste the code from `assets/script.js` into the header section of the plugin settings.

Option 2: Add to your theme
1. Navigate to **Appearance > Theme File Editor**.
2. Add the JavaScript code to your theme's `header.php` file before the closing `</head>` tag.

### 3. HTML Structure in Elementor
1. Open the desired page in **Elementor**.
2. Drag and drop an **HTML widget** onto the page.
3. Copy the HTML structure from `index.html` and paste it into the widget.
4. Save and preview the changes.

---

## File Structure
```
animated-side-menu/
├── assets/
│   ├── style.css         # CSS styles for the side menu
│   └── script.js         # JavaScript for menu animations and behavior
├── index.html            # HTML structure for Elementor integration
├── readme.md             # Documentation
```

---

## How to Import to Another Website
1. Clone the repository:
   ```bash
   git clone https://github.com/Gopalprajaapati/MENU-design.git
   ```
2. Follow the steps in the **Installation** section to add the menu to your WordPress site.

---

## Credits
- Tutorial Source:(https://www.youtube.com/watch?v=fKkfyH9thRg&ab_channel=MakeDreamWebsite)
- Developed with ❤️ by (https://makedreamwebsite.com/make-this-incredible-animated-side-menu-in-elementor/)

---

## License
This project is licensed under the [MIT License](LICENSE).

