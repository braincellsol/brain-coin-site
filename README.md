# $BRAIN Website

The last surviving braincell in crypto.

## Quick Start

Open `index.html` in your browser to preview locally.

## Deployment

### GitHub Pages
1. Create a new repo on GitHub
2. Push this folder to the repo
3. Go to Settings > Pages > Select "main" branch > Save
4. Your site will be live at `https://yourusername.github.io/repo-name`

### Vercel
1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repo
3. Deploy (zero config needed)

### Netlify
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop this folder to deploy
3. Or connect your GitHub repo

## Customization

### Add Your Logo
In `index.html`, find the `.hero-logo` div and replace:
```html
<span style="position: relative; z-index: 1;">🧠</span>
```
With:
```html
<img src="logo.png" alt="$BRAIN Logo">
```

### Update Contract Address
Search for `TBD - Coming Soon` and replace with your contract address.

### Update Buy Link
Search for `id="buy-link"` and update the `href` to your pump.fun link.

## File Structure
```
brain-coin-site/
├── index.html    # Main website (all-in-one)
├── logo.png      # Your logo (add this)
└── README.md     # This file
```
