# GameStation

A modern, responsive gaming platform featuring engaging online games. Currently hosting Cubes 2048.io, a 3D multiplayer puzzle game.

## 🎮 Featured Game

### Cubes 2048.io
- A 3D multiplayer version of the classic 2048 puzzle game
- Real-time competition with players worldwide
- Strategic gameplay with cube merging mechanics
- Responsive design for all devices

## 🚀 Tech Stack

- HTML5
- Tailwind CSS (via CDN)
- Google Fonts (Inter)
- Responsive Design
- SEO Optimized

## 💻 Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/gamestation.git
cd gamestation
```

2. Open `index.html` in your preferred browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

3. Visit `http://localhost:8000` in your browser

## 🌐 Deployment

The site is deployed at [gamestation.monster](https://gamestation.monster)

### Deployment Requirements
- Web server with HTTPS support
- Domain name configuration
- SSL certificate

### Cloudflare Workers Deployment
1. Install Wrangler CLI:
```bash
npm install -g wrangler
```

2. Login to Cloudflare:
```bash
wrangler login
```

3. Deploy your site:
```bash
wrangler deploy
```

#### Project Structure
```
gamestation/
├── index.html
├── wrangler.toml
└── src/
    └── index.js
```

#### Troubleshooting
If you encounter deployment errors:
1. Ensure you're in the correct directory containing your `index.html`
2. Verify that your `wrangler.toml` file is properly configured
3. Make sure all your files are committed to git
4. Check that you're logged in to Cloudflare (`wrangler login`)
5. Verify the project structure matches the expected layout

## 📱 Features

- Responsive design for all devices
- SEO optimized content
- Fast loading performance
- Modern UI/UX
- Cross-browser compatibility

## 🔧 Customization

### Adding New Games
1. Create a new HTML file for the game
2. Update the navigation menu
3. Add game-specific content and iframe
4. Update meta tags and SEO information

### Styling
The site uses Tailwind CSS for styling. To modify the design:
1. Edit the Tailwind classes in the HTML
2. Add custom CSS in the `<style>` section
3. Modify the color scheme in the Tailwind configuration

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

For support, please open an issue in the GitHub repository or contact the maintainers.

---

Made with ❤️ by GameStation Team 