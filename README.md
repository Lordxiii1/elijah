# Elijah Flores - Portfolio Website

A modern, responsive portfolio website showcasing skills, projects, and professional experience.

## Features

- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: Dynamic navigation, scroll animations, and hover effects
- **Contact Form**: Integrated contact form with email functionality
- **Performance Optimized**: Fast loading with lazy-loaded images
- **SEO Friendly**: Proper meta tags and semantic HTML

## Technologies Used

- HTML5
- CSS3 (Custom Properties, Flexbox, Grid)
- Vanilla JavaScript (ES6+)
- Google Fonts (Inter, Space Grotesk)

## Sections

1. **Home/Hero**: Introduction with animated code block
2. **About**: Personal information and personality traits
3. **Skills**: Programming languages, soft skills, and spoken languages
4. **Projects**: Portfolio of completed work
5. **Contact**: Contact information and form
6. **Footer**: Navigation and social links

## Setup Instructions

### For GitHub Pages Deployment:

1. **Create a GitHub Repository**
   - Go to GitHub and create a new repository
   - Name it `yourusername.github.io` (replace `yourusername` with your GitHub username)
   - Or name it anything and enable GitHub Pages in settings

2. **Upload Files**
   - Upload all files maintaining the folder structure:
     ```
     /
     ├── index.html
     ├── css/
     │   └── style.css
     ├── js/
     │   └── script.js
     └── README.md
     ```

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "GitHub Pages" section
   - Select branch (usually `main` or `master`)
   - Select folder (root `/` or `/docs`)
   - Save changes

4. **Access Your Site**
   - Your site will be available at: `https://yourusername.github.io/`
   - Or `https://yourusername.github.io/repository-name/` if using a custom repository name

### Local Development:

1. **Clone or Download**
   ```bash
   git clone <your-repo-url>
   cd portfolio
   ```

2. **Open in Browser**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Python 3
     python -m http.server 8000
     
     # Or use VS Code Live Server extension
     ```

3. **View Site**
   - Navigate to `http://localhost:8000` if using Python server
   - Or just double-click `index.html`

## Customization Guide

### Update Personal Information:

1. **Edit `index.html`**:
   - Update name, title, description in hero section
   - Modify about section content
   - Update skills and percentages
   - Change project information and links
   - Update contact information

2. **Edit `css/style.css`**:
   - Modify color scheme in `:root` variables
   - Adjust spacing, fonts, and styles
   - Customize animations

3. **Edit `js/script.js`**:
   - Update form handling logic
   - Modify animation behaviors
   - Add custom functionality

### Color Customization:

Edit the CSS variables in `css/style.css`:

```css
:root {
    --color-accent: #3b82f6;  /* Change primary accent color */
    --color-bg-primary: #0a0a0a;  /* Change background color */
    /* ... other variables ... */
}
```

### Add Projects:

In `index.html`, duplicate a project card and update:

```html
<div class="project-card">
    <div class="project-image">
        <img src="your-image-url" alt="Project Name">
        <div class="project-overlay">
            <a href="your-project-link" target="_blank" class="project-link">View Project</a>
        </div>
    </div>
    <div class="project-content">
        <h3 class="project-title">Your Project Name</h3>
        <p class="project-description">Project description here...</p>
        <div class="project-tags">
            <span class="tag">HTML</span>
            <span class="tag">CSS</span>
        </div>
    </div>
</div>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Optimized CSS with minimal dependencies
- Vanilla JavaScript (no frameworks)
- Lazy loading for images
- Efficient animations with CSS transforms

## Contact

- **Email**: elijahflores0715@gmail.com
- **Facebook**: [facebook.com/dreiixx1](https://www.facebook.com/dreiixx1/)
- **Messenger**: [m.me/dreiixx1](https://m.me/dreiixx1)

## License

© 2025 Elijah Flores. All rights reserved.

---

**Built with HTML5, CSS3 & JavaScript**