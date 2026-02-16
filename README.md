# The10 Youth Excellence Center Website

A modern, organic website for The10 Youth Excellence Center built with Astro. Features a beautiful blend of ancient yogic wisdom and modern innovation design.

## 🎨 Design Features

- **Organic & Natural Aesthetic**: Earthy color palette with flowing animations
- **Brand Colors**: Gold (#F4B41A) and Blue (#1E88E5) from The10YEC logo
- **Smooth Animations**: Page transitions, hover effects, and scroll animations
- **Fully Responsive**: Optimized for all devices
- **Zero JavaScript by Default**: Lightning-fast static pages
- **SEO Optimized**: Semantic HTML and meta tags


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


Additional pages:

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




## 📧 Contact

**The10 Youth Excellence Center**
- Address: 7600 Cottonwood St, Frisco, TX 75034
- Phone: 408-390-2871
- Email: the10yec@gmail.com

## 📄 License

© 2024 The10 Youth Excellence Center. All rights reserved.

---

**Built with love using Astro 🚀**
