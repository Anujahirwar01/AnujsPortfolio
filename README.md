# Anuj Ahirwar - Portfolio Website 🚀

A modern, responsive portfolio website showcasing your projects, skills, and experience.

## ✨ Features

- **Responsive Design** - Works perfectly on all devices
- **Modern UI/UX** - Clean, attractive design with smooth animations
- **Project Showcase** - Display your projects with live demo and GitHub links
- **Skills Section** - Interactive skill bars showing your expertise
- **Contact Form** - Allow visitors to reach out to you
- **Resume Download** - Direct download button for your resume
- **Smooth Scrolling** - Seamless navigation between sections
- **Typing Animation** - Dynamic hero section with typing effect

## 🎨 Sections

1. **Home/Hero** - Introduction with social links
2. **About** - Brief about yourself with statistics
3. **Skills** - Your technical skills with progress bars
4. **Projects** - Featured projects with live demos
5. **Contact** - Contact form and information
6. **Footer** - Social media links

## 📦 Structure

```
AnujsPortfolio/
├── index.html      # Main HTML file
├── style.css       # Styling and animations
├── script.js       # Interactive functionality
├── resume.pdf      # Your resume (add your own)
└── README.md       # This file
```

## 🚀 Getting Started

### 1. Setup Your Resume

Replace `resume.pdf` with your actual resume PDF file. Make sure it's named exactly `resume.pdf` or update the link in `index.html`.

### 2. Update Personal Information

Open `index.html` and update the following:

- **Email**: Replace `anuj@example.com` with your actual email
- **Phone**: Replace `+91 XXXXX-XXXXX` with your phone number
- **LinkedIn**: Update the LinkedIn profile URL
- **Location**: Update your location if needed

### 3. Customize Projects

Your current projects are already added:
- DPI - Deep Packet Inspection
- Tech-Kart E-Commerce Platform

To add more projects or modify existing ones:
1. Find the `projects-grid` section in `index.html`
2. Add new project cards following the existing structure
3. Update project names, descriptions, and links

### 4. Update Skills

Modify the skills in the `skills-grid` section:
- Add or remove skills
- Adjust the progress bar percentages (in the `style` attribute)

### 5. Test Locally

Simply open `index.html` in your web browser to view the portfolio.

## 🌐 Deployment

You can deploy this portfolio to:

### Vercel (Recommended)
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

### Netlify
1. Drag and drop the folder to Netlify's web interface
2. Or use Netlify CLI:
```bash
npm install netlify-cli -g
netlify deploy
```

### GitHub Pages
1. Create a GitHub repository
2. Push your code
3. Go to Settings > Pages
4. Select main branch
5. Your site will be live at `https://yourusername.github.io/repo-name`

## 🎨 Customization

### Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... more colors */
}
```

### Fonts
The portfolio uses 'Poppins' from Google Fonts. To change:
1. Update the Google Fonts link in `index.html`
2. Update `font-family` in `style.css`

### Animations
Modify animation speeds and effects in `style.css` under the `@keyframes` sections.

## 📧 Contact Form

The contact form currently shows a success message client-side. To make it fully functional:

1. Set up a backend API (Node.js/Express, etc.)
2. Or use a service like:
   - **FormSpree** (https://formspree.io/)
   - **Getform** (https://getform.io/)
   - **EmailJS** (https://www.emailjs.com/)

3. Update the form handling code in `script.js` (commented section)

## 🔧 Technologies Used

- HTML5
- CSS3 (with CSS Variables and Animations)
- JavaScript (ES6+)
- Font Awesome (for icons)
- Google Fonts (Poppins)

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

Feel free to use this portfolio template for your personal use.

## 🤝 Support

If you have any questions or need help customizing, feel free to reach out!

---

**Made with ❤️ by Anuj Ahirwar**
