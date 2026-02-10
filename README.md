# goddy_voicePro

Dark minimal multi-page artist website template built with **Astro** and deployed on **Netlify**.

Designed for creators who value **speed**, **clarity**, and **aura**.

---

## ✨ Features

- 🎨 **Dark Minimal Aesthetic** - Clean, distraction-free design
- ⚡ **Ultra Fast** - Static site generation with Astro
- 📱 **Fully Responsive** - Works on all devices
- 🚀 **Netlify Ready** - Deploy in seconds
- 📝 **Easy Customization** - Simple configuration file
- 🔗 **Multi-Page** - Home, About, Music, Contact pages included
- 🎯 **SEO Optimized** - Built-in meta tags and structure

---

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ installed
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/goddyboyrecords-dotcom/goddy_voicePro.git
cd goddy_voicePro

# Install dependencies
npm install

# Start development server
npm run dev
```

Visit `http://localhost:3000` to see your site live!

---

## 🛠 Customize

### 1. Update Your Info
Edit `src/data/siteConfig.js`:
```javascript
export const siteConfig = {
  name: "Your Name",
  tagline: "Your tagline here",
  description: "Your description",
  socials: {
    spotify: "your-spotify-url",
    audiomack: "your-audiomack-url",
    soundcloud: "your-soundcloud-url"
  },
  contactEmail: "your-email@example.com"
};
```

### 2. Edit Pages
- `src/pages/index.astro` - Home page
- `src/pages/about.astro` - About page
- `src/pages/music.astro` - Music links page
- `src/pages/contact.astro` - Contact page

### 3. Customize Styles
Edit `src/styles/global.css` to change colors, fonts, and spacing.

### 4. Add Images
Place images in `public/images/` and reference them as `/images/filename.jpg`

---

## 📚 Documentation

See [docs/customization.md](docs/customization.md) for detailed customization guide.

---

## 🌍 Deployment

### Deploy to Netlify (Recommended)

1. Push your repository to GitHub
2. Go to [netlify.com](https://netlify.com)
3. Click **New site from Git**
4. Select your repository
5. Click **Deploy site**

That's it! Netlify automatically builds and deploys on every push.

### Deploy to Other Platforms

#### Vercel
```bash
npm install -g vercel
vercel
```

#### GitHub Pages
```bash
npm run build
# Upload `dist` folder to GitHub Pages
```

---

## 📂 Project Structure

```
goddy_voicePro/
├── README.md                 # This file
├── LICENSE                   # MIT License
├── .gitignore               # Git ignore rules
├── package.json             # Dependencies & scripts
├── astro.config.mjs         # Astro configuration
├── netlify.toml             # Netlify configuration
├── public/                  # Static assets
│   └── images/
├── src/
│   ├── layouts/
│   │   └── BaseLayout.astro # Main layout
│   ├── pages/               # Auto-routed pages
│   │   ├── index.astro      # Home (/)
│   │   ├── about.astro      # About (/about)
│   │   ├── music.astro      # Music (/music)
│   │   └── contact.astro    # Contact (/contact)
│   ├── components/          # Reusable components
│   ├── data/
│   │   └── siteConfig.js    # Site configuration
│   └── styles/
│       └── global.css       # Global styles
├── docs/
│   └── customization.md     # Customization guide
└── .github/
    └── workflows/
        └── deploy.yml       # GitHub Actions CI/CD
```

---

## 🎨 Color Palette (Customizable)

- **Background**: `#0a0a0a` (Almost black)
- **Text**: `#e0e0e0` (Light gray)
- **Borders**: `#333` (Dark gray)
- **Hover**: `#fff` (White)

Edit `src/styles/global.css` to change these values.

---

## 📝 Scripts

```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run preview  # Preview production build locally
```

---

## 🤝 Contributing

This is a template. Feel free to fork and customize it for your own project!

---

## 📄 License

MIT License - See [LICENSE](LICENSE) file for details.

---

## 🙌 Support

For questions or issues:
- Check the [docs/customization.md](docs/customization.md) file
- Review [Astro documentation](https://docs.astro.build)
- Visit [Netlify documentation](https://docs.netlify.com)

---

**Built with ❤️ for creators with a message.**