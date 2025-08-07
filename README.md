# Wayne Pan - Personal Portfolio

A modern, responsive personal portfolio website showcasing research, projects, and professional information.

## 🚀 Quick Start

1. **Clone this repository** to your GitHub Pages repository (`username.github.io`)
2. **Customize the content** by editing `index.html`
3. **Update your information** in the sections below
4. **Add your images** to the `images/` folder
5. **Push to GitHub** - your site will be live at `https://username.github.io`

## 📝 Customization Guide

### Personal Information
Replace the following placeholders in `index.html`:

- **Name**: "Wayne Pan" (line 32, 36)
- **Title/Role**: "Graduate Student & Researcher" (line 37)
- **Description**: Update the hero description (lines 38-40)
- **Field/Area**: Replace "[Your Field/Area of Interest]" (line 39)
- **Email**: Update email links (lines 50, 180)
- **Social Links**: Update LinkedIn, GitHub, ORCID URLs (lines 47-55)
- **Location**: Update your city/country (line 186)

### About Section
- Update the about text (lines 72-78)
- Replace skill tags with your actual skills (lines 84-87)
- Add your photo: Replace the placeholder in the about section

### Research Section
1. **Research Projects**: Update the research cards (lines 100-130)
   - Project titles and descriptions
   - Status (ongoing/published)
   - Tags (research areas)
   - Links to papers, code, datasets

2. **Publications**: Update the publications list (lines 135-145)
   - Publication titles
   - Author names
   - Conference/journal information
   - DOI and PDF links

### Projects Section
Update the project cards (lines 160-200):
- Project names and descriptions
- Technology tags
- GitHub repository links
- Live demo links
- Project images

### Contact Information
- Update email address (line 180)
- Update LinkedIn profile (line 186)
- Update location (line 192)

## 🎨 Styling

The website uses CSS custom properties for easy theming. You can modify colors in `css/style.css`:

```css
:root {
    --primary-color: #2563eb;    /* Main accent color */
    --secondary-color: #64748b;  /* Secondary text */
    --accent-color: #f8fafc;     /* Background accent */
    --text-primary: #1e293b;     /* Main text */
    --text-secondary: #64748b;   /* Secondary text */
}
```

## 📱 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Modern UI**: Clean, professional design with smooth animations
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Performance**: Optimized loading and smooth scrolling
- **Accessibility**: ARIA labels and keyboard navigation support

## 🖼️ Adding Images

1. **Profile Photo**: Add your photo to `images/profile.jpg` and update the img src in the about section
2. **Project Images**: Add project screenshots to `images/projects/` and update the project cards
3. **Research Images**: Add any research-related images to `images/research/`

## 📁 File Structure

```
waynepancw.github.io/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # All styles
├── js/
│   └── script.js       # Interactive functionality
├── images/             # Your images
│   ├── profile.jpg     # Your profile photo
│   ├── projects/       # Project screenshots
│   └── research/       # Research-related images
└── README.md           # This file
```

## 🚀 Deployment

This portfolio is designed for GitHub Pages:

1. **Create a repository** named `your-username.github.io`
2. **Upload these files** to the repository
3. **Enable GitHub Pages** in repository settings
4. **Your site will be live** at `https://your-username.github.io`

## 🔧 Advanced Customization

### Adding New Sections
To add a new section:
1. Add the HTML section in `index.html`
2. Add navigation link in the navbar
3. Add corresponding styles in `style.css`
4. Update the JavaScript navigation handling

### Contact Form
The contact form currently shows an alert. To make it functional:
1. Set up a form handler (Formspree, Netlify Forms, etc.)
2. Update the form action in `index.html`
3. Modify the JavaScript form handling in `script.js`

### Analytics
Add Google Analytics by including the tracking code in the `<head>` section of `index.html`.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🤝 Contributing

Feel free to customize this template for your own use. If you make improvements, consider sharing them back with the community.

## 📄 License

This template is free to use and modify for personal and commercial purposes.

---

**Next Steps:**
1. Update all placeholder content with your information
2. Add your actual photos and project images
3. Test the site locally by opening `index.html` in a browser
4. Deploy to GitHub Pages
5. Add the link to your resume/CV

Good luck with your job search! 🎉