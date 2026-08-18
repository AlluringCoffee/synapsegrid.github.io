# Synapse Grid - Official Landing Page

![Synapse Grid](https://img.shields.io/badge/Status-In%20Development-blue)
![Platform](https://img.shields.io/badge/Platform-Steam-black)

**Synapse Grid** is neon bike combat. Lay a wall, ride the green ones, die on amber.

This repository hosts the public landing page for Synapse Grid: Neon Bike Combat, a solo indie game built with Godot by Timothy Bunce (AlluringCoffee).

## 🌐 Live Site

**GitHub Pages URL**: [alluringcoffee.github.io/synapsegrid.github.io](https://alluringcoffee.github.io/synapsegrid.github.io/)

## 🎮 About the Game

Synapse Grid is a high-speed neon light-cycle racer where:
- **Your trail becomes the arena** — Every move leaves a wall behind you
- **Green is life** — Rideable surfaces you can navigate and use
- **Amber is death** — The lethal lane edge that ends your run
- **Strategy meets reflex** — Pierce through walls, create paths, dominate the grid

### Status
- **Development**: Active
- **Platform**: PC (Steam)
- **Release**: TBA
- **Developer**: Solo indie (Timothy Bunce / AlluringCoffee)
- **Engine**: Godot

## 🛠️ Repository Structure

```
synapsegrid.github.io/
├── index.html              # Main landing page (synthwave design)
├── _config.yml            # Jekyll configuration
├── privacy.md             # Synapse Grid privacy policy
├── level_it_privacy.md    # Level-It Tool privacy policy
└── README.md             # This file
```

## 📝 Updating the Steam Link

When the Steam App ID becomes available:

1. Open `index.html`
2. Find the Steam CTA section (around line 148-151)
3. Replace the disabled button:
   ```html
   <button class="steam-cta disabled" disabled>
       Wishlist on Steam — Page Coming Soon
   </button>
   ```
   
   With a live link:
   ```html
   <a href="https://store.steampowered.com/app/YOUR_APP_ID" class="steam-cta" target="_blank" rel="noopener">
       Wishlist on Steam
   </a>
   ```

4. Commit and push to `main`
5. GitHub Pages will automatically rebuild

## 🖼️ Adding Screenshots

To add gameplay screenshots:

1. Create an `assets` or `images` folder
2. Upload your screenshots (16:9 aspect ratio recommended)
3. In `index.html`, replace the `.screenshot-placeholder` divs with:
   ```html
   <img src="assets/screenshot1.jpg" alt="Synapse Grid gameplay">
   ```

## 🔧 Local Development

To test locally:

```bash
# Serve with Python
python -m http.server 8000

# Or use Jekyll (if installed)
bundle exec jekyll serve

# Then visit http://localhost:8000 (or :4000 for Jekyll)
```

## 📄 Privacy Policies

This repository hosts privacy policies for:
- **Synapse Grid** (game) — [privacy.html](https://alluringcoffee.github.io/synapsegrid.github.io/privacy.html)
- **Level-It Tool** (utility app) — [level_it_privacy.html](https://alluringcoffee.github.io/synapsegrid.github.io/level_it_privacy.html)

Both are accessible from the footer of the landing page.

## 🚀 Deployment

This site uses **GitHub Pages** with Jekyll:

1. Push changes to the `main` branch
2. GitHub Pages automatically rebuilds (usually takes 1-2 minutes)
3. Changes appear at the live URL

### First-Time Setup

If GitHub Pages is not enabled:

1. Go to **Settings** → **Pages**
2. Source: Select `main` branch
3. Folder: `/ (root)`
4. Click **Save**

## 📧 Contact

- **Developer**: Timothy Bunce (AlluringCoffee)
- **Support**: See privacy policies for contact information

## 📜 License

© 2026 Timothy Bunce / AlluringCoffee. All rights reserved.
