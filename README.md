# 🔥❄️ LAZY RAG - Landing Page

**Official website for lazyrag.one**

## 🚀 Quick Start

Open `index.html` in a browser or serve it locally:

```bash
# Python 3
python3 -m http.server 8080

# Node.js (if you have http-server installed)
npx http-server -p 8080
```

Then visit: `http://localhost:8080`

## 📁 Project Structure

```
lazyrag-website/
├── index.html           # Main landing page (Steel, Fire & Ice theme)
├── assets/              # Images, icons, og-image.png
├── docs/                # Additional documentation
└── README.md            # This file
```

## 🎨 Theme

**Steel, Fire & Ice**

- **Steel**: Industrial foundation (gradient backgrounds)
- **Fire**: Power and action (#FF6B35 orange for CTAs)
- **Ice**: Performance and victory (#00D4FF cyan for metrics)

## ✨ Features

- ✅ WolfejamGizmo signature theme toggle (half-moon design)
- ✅ Full-page comparison hero (22x faster messaging)
- ✅ Real benchmark data table with alternating columns
- ✅ Fully responsive (mobile-first)
- ✅ Accessible (ARIA, keyboard navigation, reduced motion)
- ✅ SEO optimized (Open Graph, structured data)
- ✅ Zero dependencies (pure HTML/CSS/JS)

## 🌐 Domains

- **Primary**: lazyrag.one
- **Backup**: lazyrag.cloud

Both secured at Namecheap.

## 🏗️ Deployment Options

### Option 1: Vercel (Recommended)
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
cd /Users/wolfejam/RAG/lazyrag-website
vercel

# Connect custom domain at vercel.com dashboard
```

### Option 2: Netlify
```bash
# Install Netlify CLI
npm i -g netlify-cli

# Deploy
cd /Users/wolfejam/RAG/lazyrag-website
netlify deploy --prod

# Connect custom domain at netlify.app dashboard
```

### Option 3: GitHub Pages
```bash
# Push to GitHub, enable Pages in Settings
# Point to main branch, root directory
```

## 📊 Benchmark Data

All performance claims validated with real tests:
- **Pinecone**: 425ms avg (21.6x slower)
- **Weaviate**: 434ms avg (22.1x slower)
- **LAZY RAG**: 19.7ms avg ⚡

Full results in benchmark table on landing page.

## 🔧 Configuration

### DNS Setup (Namecheap)
1. Log in to Namecheap
2. Go to Domain List → Manage → Advanced DNS
3. Add A records pointing to deployment provider's IP
4. Or add CNAME record pointing to deployment URL

### Analytics (Optional)
Add Google Analytics or Plausible script before `</head>` tag.

## 📝 TODO

- [ ] Create og-image.png (1200x630px with LAZY RAG branding)
- [ ] Add favicon.ico
- [ ] Set up analytics
- [ ] Configure DNS at Namecheap
- [ ] Deploy to production
- [ ] Test on mobile devices
- [ ] Create GitHub public repo (for buyers to inspect)

## 🏎️ Built With

Part of the **Context-On-Demand** vision - F1-inspired software engineering.

**Made with precision. Built for speed. Designed to delight.** 🏎️⚡
