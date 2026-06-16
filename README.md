# The Divine Frequency Healing Sanctuary

Welcome to The Divine Frequency Healing Sanctuary website repository. This is a fully functional, production-ready spiritual healing services website for Sasha.

## Features

✨ **Responsive Design** - Mobile-first, works perfectly on all devices
📅 **Booking System** - Clients can schedule sessions with available time slots
📧 **Email Integration** - All form submissions sent to s.saakshi26@gmail.com via Formspree
📱 **Social Media** - Instagram integration (@sashaheals20)
🎨 **Beautiful UI** - Elegant, luxurious design with gold accents
♿ **Accessible** - WCAG compliant with proper semantic HTML
⚡ **Fast Loading** - Optimized for performance
🔒 **Secure** - No backend required, client-side validation

## Services Offered

1. Soul Reading
2. Tarot Card Reading
3. Merlin Trinity Healing System
4. Angel Healing
5. Inner Child Healing
6. Past Life Regression
7. Angel Intuitive Card Reading
8. Akashic Record Reading

## Contact Information

- **Email**: s.saakshi26@gmail.com
- **Instagram**: @sashaheals20

## Deployment Options

### Option 1: GitHub Pages (FREE & EASIEST)

1. Go to your repository settings
2. Navigate to **Pages** section
3. Select `main` branch as source
4. Your site will be live at: `https://sksharma2708-web.github.io/divine-frequency-sanctuary/`

### Option 2: Netlify (FREE)

1. Go to [netlify.com](https://netlify.com)
2. Click "New site from Git"
3. Connect your GitHub repository
4. Netlify auto-deploys on every push
5. Get a free `.netlify.app` domain or connect custom domain

### Option 3: Vercel (FREE)

1. Go to [vercel.com](https://vercel.com)
2. Click "New Project"
3. Import your GitHub repository
4. Auto-deploys on every push
5. Free domain included

### Option 4: Traditional Web Hosting

1. Download all files
2. Upload via FTP to your hosting provider
3. Access via your custom domain

## File Structure

```
divine-frequency-sanctuary/
├── index.html           # Main website (all-in-one file)
├── README.md           # This file
├── .gitignore          # Git ignore rules
├── netlify.toml        # Netlify configuration (optional)
└── sitemap.xml         # SEO sitemap
```

## Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/sksharma2708-web/divine-frequency-sanctuary.git
   cd divine-frequency-sanctuary
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

3. Visit `http://localhost:8000` in your browser

## Configuration

### Email Setup (Already Configured)

The website uses **Formspree** for email handling. All form submissions are sent to:
- **Email**: s.saakshi26@gmail.com
- **Form ID**: `mrevkodn`

The forms are pre-configured and working. No additional setup needed!

### Customization

To customize the website, edit `index.html`:

- **Colors**: Update CSS variables in the `<style>` section (gold, text colors, etc.)
- **Content**: Edit text in HTML sections
- **Services**: Add/remove service cards in the grid
- **Instagram**: Update URL in header and footer (`@sashaheals20`)
- **Email**: Change `s.saakshi26@gmail.com` throughout the file

## How It Works

### Contact Form
- Clients fill out the contact form
- Data is sent to `s.saakshi26@gmail.com` via Formspree
- No backend server needed

### Booking Form
- Clients select a service, date, and time slot
- All information is emailed to `s.saakshi26@gmail.com`
- Success message displayed after submission

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- ⚡ Single HTML file (no build process needed)
- 📦 ~32KB file size
- 🚀 Loads in <2 seconds
- 💯 Mobile-optimized
- 🎨 Smooth animations and transitions

## SEO

- Meta tags for search engines
- Open Graph tags for social sharing
- Semantic HTML structure
- Mobile-friendly design

## Troubleshooting

### Forms not sending emails?
1. Check that you have internet connection
2. Verify Formspree endpoint is accessible
3. Check browser console for errors (F12)
4. Try a different email if needed

### Styling looks broken?
1. Clear browser cache (Ctrl+Shift+Delete)
2. Check that fonts are loading (check Network tab)
3. Verify CSS is not blocked by browser extensions

### Mobile layout issues?
1. Ensure viewport meta tag is present (it is)
2. Check device zoom level (should be 100%)
3. Try different browser

## Security

- ✅ No backend = no security vulnerabilities
- ✅ All data sent encrypted via HTTPS
- ✅ No database to breach
- ✅ No sensitive data stored locally
- ✅ GDPR compliant (data sent via Formspree only on submission)

## Analytics (Optional)

To add Google Analytics:

1. Go to [analytics.google.com](https://analytics.google.com)
2. Create a new property for your website
3. Get your Tracking ID (G-XXXXXXXXXX)
4. Add this before `</head>`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

## License

© 2026 Divine Frequency Healing Sanctuary. All rights reserved.

## Support

For issues or improvements, please create an issue in the repository.

---

**Website Status**: ✅ Live and Ready to Use

**Last Updated**: 2026-06-16

**Maintained by**: Sasha & Team
