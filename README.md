# The10 Youth Excellence Center Website

A modern, organic website for The10 Youth Excellence Center built with Astro. Features a beautiful blend of ancient yogic wisdom and modern innovation design.

## 🎨 Design Features

- **Organic & Natural Aesthetic**: Earthy color palette with flowing animations
- **Brand Colors**: Gold (#F4B41A) and Blue (#1E88E5) from The10YEC logo
- **Smooth Animations**: Page transitions, hover effects, and scroll animations
- **Fully Responsive**: Optimized for all devices
- **Zero JavaScript by Default**: Lightning-fast static pages
- **SEO Optimized**: Semantic HTML and meta tags

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ installed
- npm or yarn package manager

### Installation

1. **Install dependencies**
```bash
npm install
```

2. **Run development server**
```bash
npm run dev
```

The site will be available at `http://localhost:4321`

3. **Build for production**
```bash
npm run build
```

4. **Preview production build**
```bash
npm run preview
```

## 📁 Project Structure

```
the10yec/
├── src/
│   ├── layouts/
│   │   └── BaseLayout.astro      # Main layout with nav & footer
│   ├── pages/
│   │   ├── index.astro            # Homepage
│   │   ├── about/                 # About pages
│   │   ├── programs/              # Program pages
│   │   │   ├── yoga.astro        # Yoga program (completed)
│   │   │   ├── entrepreneurship.astro  # TODO
│   │   │   ├── technology.astro   # TODO
│   │   │   └── sharing.astro      # TODO
│   │   ├── resources/             # Resources pages
│   │   └── join/                  # Join pages
│   ├── components/                # Reusable components
│   └── styles/
│       └── global.css             # Global styles & variables
├── public/                        # Static assets
├── astro.config.mjs
├── package.json
└── README.md
```

## 🎯 Pages Completed

✅ **Homepage** - Full featured with:
- Hero section with animated lotus mandala
- Why The10 Exists section
- Triad of 3 Pillars
- Programs overview
- Philosophy section
- Centers section
- CTA section

✅ **Yoga Program Page** - Complete with:
- Program overview
- 8 Limbs of Yoga
- Yama & Niyama detailed
- Samyama (Mind Mastery)
- Benefits & Flow

✅ **Base Layout** - Navigation and Footer:
- Fixed navigation with dropdowns
- Mobile-responsive menu
- Comprehensive footer with all links

## 📝 To Do

Create additional pages:

### About Section
- `/about/vision` - Vision & Purpose
- `/about/philosophy` - The10 Philosophy
- `/about/team` - Meet the Team

### Programs
- `/programs/entrepreneurship` - Entrepreneurship program details
- `/programs/technology` - Technology program details
- `/programs/sharing` - Sharing & Service details
- `/programs` - Programs overview page

### Resources
- `/resources/sutras` - Sutras & Teachings
- `/resources/practices` - Practices & Tools

### Other
- `/join` - Join Us page
- `/contact` - Contact page

## 🎨 Customization

### Colors
Edit `src/styles/global.css` to customize the color palette:
```css
:root {
  --gold: #F4B41A;
  --blue: #1E88E5;
  /* ... more colors */
}
```

### Content
All content is in `.astro` files. Edit the files in `src/pages/` to update content.

### Logo
Replace the text logo in `src/layouts/BaseLayout.astro` with an image:
```html
<img src="/logo.png" alt="The10 YEC" class="logo-image" />
```

## 🚀 Deployment

### Netlify
1. Push your code to GitHub
2. Connect your repo to Netlify
3. Build command: `npm run build`
4. Publish directory: `dist`

### Vercel
1. Push your code to GitHub
2. Import project in Vercel
3. Framework Preset: Astro
4. Deploy!

### GitHub Pages
```bash
npm run build
# Upload the `dist` folder to your gh-pages branch
```

## 🛠️ Adding New Pages

1. Create a new `.astro` file in `src/pages/`
2. Import the BaseLayout
3. Add your content
4. The page will automatically be available at its file path

Example:
```astro
---
import BaseLayout from '../layouts/BaseLayout.astro';
---

<BaseLayout title="My New Page">
  <section class="section">
    <div class="container">
      <h1>My New Page</h1>
      <p>Content goes here</p>
    </div>
  </section>
</BaseLayout>
```

## 📧 Contact

**The10 Youth Excellence Center**
- Address: 7600 Cottonwood St, Frisco, TX 75034
- Phone: 408-390-2871
- Email: the10yec@gmail.com

## 📄 License

© 2024 The10 Youth Excellence Center. All rights reserved.

---

**Built with love using Astro 🚀**
