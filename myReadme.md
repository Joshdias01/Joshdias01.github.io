# Modern Portfolio Website

A clean, modern, and responsive portfolio website built with pure HTML, CSS, and JavaScript. Features a unique glass-morphism design, smooth animations, and mobile-first approach.

## 🌟 Features

- **Modern Design**: Glass-morphism effects and gradient backgrounds
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Fade-in effects, hover animations, and scroll-based triggers
- **Interactive Elements**: Dynamic navigation, contact form, and back-to-top button
- **Performance Optimized**: Fast loading with optimized images and code
- **Accessibility**: WCAG compliant with proper focus states and semantic HTML
- **SEO Ready**: Structured data and meta tags

## 🚀 Quick Start

### Option 1: GitHub Pages Deployment

1. **Fork or Download** this repository
2. **Create a new repository** on GitHub named `your-username.github.io`
3. **Upload the files** to your repository
4. **Enable GitHub Pages** in repository settings
5. **Access your site** at `https://your-username.github.io`

### Option 2: Custom Domain with GitHub Pages

1. Follow steps 1-3 above
2. Add a `CNAME` file with your domain name
3. Configure DNS settings with your domain provider
4. Enable GitHub Pages with custom domain

## 📁 Project Structure

```
portfolio-website/
├── index.html              # Main HTML file
├── style.css              # All styling and animations
├── script.js              # JavaScript functionality
├── README.md              # This file
└── assets/                # Images and media files
    ├── profile-photo.jpg  # Your profile picture
    ├── project1.jpg       # Project screenshots
    ├── project2.jpg
    ├── project3.jpg
    └── resume.pdf         # Your resume file
```

## ⚙️ Customization Guide

### 1. Personal Information

**Update in `index.html`:**
- Change "Your Name" to your actual name
- Update the tagline and description
- Modify contact information
- Add your social media links

### 2. Profile Photo

- Replace `assets/profile-photo.jpg` with your photo
- Recommended size: 400x400px (square format)
- Optimize for web (keep file size under 500KB)

### 3. Projects Section

**For each project:**
- Replace project images in the `assets/` folder
- Update project titles and descriptions
- Modify technology tags
- Add your project and GitHub links

### 4. Skills and Education

**In the About section:**
- Update your bio text
- Modify skills lists (Frontend, Backend, Tools)
- Change education information

### 5. Contact Form Setup

**Formspree Integration:**
1. Go to [Formspree.io](https://formspree.io)
2. Create an account and get your form endpoint
3. Replace `YOUR_FORM_ID` in the form action URL
4. Test the form functionality

### 6. Resume

- Add your resume as `assets/resume.pdf`
- Make sure the download link works

### 7. Color Scheme

**Modify CSS variables in `style.css`:**
```css
:root {
    --primary-color: #667eea;     /* Main brand color */
    --secondary-color: #764ba2;   /* Secondary brand color */
    --accent-color: #f093fb;      /* Accent highlights */
    /* Modify other colors as needed */
}
```

## 🎨 Customization Examples

### Change Color Theme
```css
/* Blue to Green Theme */
:root {
    --primary-color: #10B981;
    --secondary-color: #059669;
    --accent-color: #34D399;
}
```

### Add New Project
```html
<div class="project-card">
    <div class="project-image">
        <img src="assets/new-project.jpg" alt="Project Name">
        <div class="project-overlay">
            <div class="project-links">
                <a href="project-url" class="project-link" target="_blank">
                    <i class="fas fa-external-link-alt"></i>
                </a>
                <a href="github-url" class="project-link" target="_blank">
                    <i class="fab fa-github"></i>
                </a>
            </div>
        </div>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
    </div>
</div>
```

## 📱 Mobile Optimization

The website is fully responsive with:
- Mobile-first CSS approach
- Touch-friendly navigation
- Optimized images for different screen sizes
- Readable typography on small screens

## 🔧 Technical Features

- **Pure HTML/CSS/JS**: No frameworks or dependencies
- **CSS Grid & Flexbox**: Modern layout techniques
- **Intersection Observer**: Efficient scroll animations
- **CSS Custom Properties**: Easy theming
- **Form Validation**: Client-side validation with feedback
- **Lazy Loading**: Images load as needed
- **Progressive Enhancement**: Works without JavaScript

## 🚀 Performance Tips

1. **Optimize Images**: Use WebP format for better compression
2. **Minify CSS/JS**: Use build tools for production
3. **Enable Caching**: Configure proper cache headers
4. **CDN Usage**: Consider using a CDN for assets
5. **Lazy Loading**: Images load when needed

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📋 Deployment Checklist

- [ ] Replace all placeholder text with your information
- [ ] Add your profile photo and project images
- [ ] Update all links (social media, projects, resume)
- [ ] Configure Formspree for contact form
- [ ] Test on multiple devices and browsers
- [ ] Optimize images for web
- [ ] Set up Google Analytics (optional)
- [ ] Configure custom domain (optional)

## 🎯 SEO Optimization

**Recommended additions:**
```html
<!-- In <head> section -->
<meta name="description" content="Your professional description">
<meta name="keywords" content="your, skills, keywords">
<meta property="og:title" content="Your Name - Portfolio">
<meta property="og:description" content="Your description">
<meta property="og:image" content="assets