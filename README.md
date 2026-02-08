# TradeHax - Gaming & Web3 Platform

Welcome to TradeHax, a gaming and Web3 platform featuring retro games, blockchain integration, and interactive experiences.

## 🌐 Live Site

Visit us at: [https://tradehax.net](https://tradehax.net)

## 🎮 Features

- **Retro Gaming Hub**: Play classic games like Mario, Zelda, Tetris, Snake, and more
- **Web3 Integration**: Blockchain-powered features and rewards
- **Interactive Dashboard**: Track your gaming progress and achievements
- **Modern UI**: Built with Next.js, React, and Tailwind CSS

## 🚀 Quick Start

### For GitHub Pages Deployment

This site is configured for GitHub Pages deployment. The repository includes:

- `.nojekyll` file for proper asset serving
- `CNAME` file configured for custom domain (tradehax.net)
- Static HTML pages for quick loading
- Next.js app for dynamic features

### Local Development

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Start production server
npm start
```

Visit `http://localhost:3000` to see the site.

## 📁 Project Structure

```
/
├── app/              # Next.js app directory
├── components/       # React components
├── public/          # Static assets
├── lib/             # Utility functions
├── types/           # TypeScript types
├── *.html           # Static game pages
└── index.html       # Main landing page
```

## 🔧 Configuration

### Custom Domain Setup

1. In your domain registrar (Namecheap), add the following DNS records:
   ```
   Type: A
   Host: @
   Value: 185.199.108.153
   Value: 185.199.109.153
   Value: 185.199.110.153
   Value: 185.199.111.153
   ```

2. Add CNAME record:
   ```
   Type: CNAME
   Host: www
   Value: ketlticknots.github.io
   ```

3. The `CNAME` file in this repository is already configured with `tradehax.net`

### GitHub Pages Settings

1. Go to Repository Settings → Pages
2. Source: Deploy from branch
3. Branch: Select your deployment branch
4. Custom domain: tradehax.net
5. Enforce HTTPS: ✓ (enabled)

## 🔒 Security

- HTTPS enforced for all connections
- Content Security Policy headers configured
- XSS protection enabled
- Regular security audits

See [SECURITY.md](SECURITY.md) for more details.

## 📦 Technologies

- **Frontend**: Next.js 15, React 19, TypeScript
- **Styling**: Tailwind CSS
- **Blockchain**: Solana Web3.js, Anchor
- **Build**: Node.js, npm

## 📝 License

All rights reserved.

## 🤝 Contributing

This is a private project. For questions or issues, please contact the repository owner.

---

Built with ❤️ for the gaming and Web3 community
