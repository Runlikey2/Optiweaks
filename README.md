# Optiweaks Website

Modern, professional website for Optiweaks Windows System Optimizer.

## 🚀 Quick Deploy

### First Time Setup
If you need to re-download images:
```bash
python download_images.py  # Downloads game images from Hypertune
python update_html.py      # Updates HTML to use local paths
```
Or simply run: `setup_images.bat`

### GitHub Pages
1. Create a new repository on GitHub
2. Drag and drop all files from this folder to the repo
3. Go to Settings → Pages
4. Select "Deploy from branch" → main → root
5. Your site will be live at `https://yourusername.github.io/repo-name`

### Netlify
1. Drag and drop this folder to [Netlify Drop](https://app.netlify.com/drop)
2. Done! Instant deployment

### Vercel
1. Import this folder to Vercel
2. Deploy with one click

## 📁 Structure

```
website/
├── index.html              # Main page
├── style.css               # All styles
├── README.md               # This file
├── images/
│   ├── games/              # Game carousel images (9 images)
│   └── screenshots/        # App screenshots (6 images)
├── download_images.py      # Script to download images
├── update_html.py          # Script to update HTML paths
├── setup_images.bat        # Run both scripts
└── download_icons.html     # Icon reference (optional)
```

## 🎨 Features

- ✅ Green accent color scheme (#22c55e)
- ✅ Auto-scrolling game carousel with local images
- ✅ Performance stats showcase
- ✅ Full-height hero section
- ✅ Responsive design
- ✅ FAQ section
- ✅ No build process needed
- ✅ Pure HTML/CSS/JS
- ✅ All images downloaded locally (no external dependencies)

## 🔧 Customization

### Colors
Edit CSS variables in `style.css`:
```css
:root {
    --accent-primary: #22c55e;  /* Main green */
    --bg-primary: #000000;      /* Background */
}
```

### Download Link
Update the download button href in `index.html`:
```html
<a href="YOUR_DOWNLOAD_LINK_HERE" class="btn-primary">
```

### Game Performance Stats
Edit the games array in the `<script>` section:
```javascript
const games = [
    { name: 'VALORANT', boost: '30-120' },
    // Add more games...
];
```

## 📸 Screenshots

The website currently uses `promo_1.png` as placeholder for all 6 screenshot slots. To add your actual Optiweaks screenshots:

1. Take screenshots of your app
2. Save them as `screenshot1.png` through `screenshot6.png` in `images/screenshots/`
3. They'll automatically appear on the website

Recommended screenshots:
- screenshot1.png: Network Optimization page
- screenshot2.png: Hardware Tweaks page
- screenshot3.png: Game Mode page
- screenshot4.png: Debloat Tools page
- screenshot5.png: Performance Monitor
- screenshot6.png: Advanced Settings

## 🌐 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

## 📝 License

Free to use for Optiweaks project.

## 🔗 Links

- [Optiweaks GitHub](https://github.com/yourusername/optiweaks)
- [Download Optiweaks](https://github.com/yourusername/optiweaks/releases)
