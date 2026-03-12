# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript to showcase your professional experience, projects, and skills.

## 🚀 Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: 
  - Smooth scrolling navigation
  - Animated skill bars
  - Project card hover effects
  - Contact form with validation
  - Mobile-friendly hamburger menu
- **Performance Optimized**: Lazy loading, debounced scroll events
- **SEO Friendly**: Semantic HTML5 structure
- **Accessible**: WCAG compliant markup

## 📁 Project Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # Complete CSS styling
├── script.js           # Interactive JavaScript features
└── README.md           # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup for better accessibility and SEO
- **CSS3**: Modern features including Grid, Flexbox, and animations
- **JavaScript (ES6+)**: Interactive features and form handling
- **Google Fonts**: Inter font for typography
- **Font Awesome**: Icon library for social links and UI elements

## 📋 Sections Included

1. **Navigation**: Fixed header with smooth scroll links
2. **Hero**: Eye-catching introduction with call-to-action buttons
3. **About**: Personal background and key highlights
4. **Experience**: Professional timeline with work history
5. **Projects**: Featured projects with technology tags
6. **Skills**: Technical skills with progress bars and categories
7. **Contact**: Contact form and professional information
8. **Footer**: Copyright and attribution

## 🚀 Quick Start

1. **Clone or Download** the project files
2. **Open `index.html`** in your web browser
3. **Customize** the content with your personal information

### Local Development

For development with live reload:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 🎨 Customization Guide

### Personal Information

Update the following placeholders in `index.html`:

- **Your Name**: Replace all instances of "Your Name"
- **Contact Info**: Update email, phone, and location
- **Social Links**: Replace with your actual social media URLs
- **Professional Title**: Update your job title and description

### Experience Section

Modify the timeline items in the Experience section:

```html
<div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
        <div class="timeline-header">
            <h3>Your Job Title</h3>
            <span class="timeline-date">Start Year - End Year</span>
        </div>
        <h4>Company Name</h4>
        <ul>
            <li>Your achievement or responsibility</li>
            <li>Another key accomplishment</li>
        </ul>
    </div>
</div>
```

### Projects Section

Update project cards with your actual projects:

```html
<div class="project-card">
    <div class="project-image">
        <!-- Add your project screenshot here -->
        <img src="project-screenshot.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="live-demo-url" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
            <a href="github-url" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
        </div>
    </div>
</div>
```

### Skills Section

Update your technical skills and adjust progress bars:

```html
<div class="skill-item">
    <span>Skill Name</span>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 85%"></div>
    </div>
</div>
```

### Color Scheme

Modify the CSS variables in `styles.css` to customize colors:

```css
:root {
    --primary-color: #2563eb;    /* Main brand color */
    --secondary-color: #1e40af;  /* Darker shade */
    --accent-color: #3b82f6;     /* Lighter shade */
    /* ... other color variables */
}
```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 767px and below

## 🔧 Advanced Features

### Contact Form Integration

The contact form is currently set up for demonstration. To make it functional:

1. **Backend Integration**: Connect to a service like Formspree, Netlify Forms, or your own backend
2. **Email Service**: Integrate with EmailJS or similar service
3. **Server-side Processing**: Set up a Node.js/PHP backend

Example Formspree integration:

```html
<form action="https://formspree.io/f/your-form-id" method="POST">
    <!-- Your form fields -->
</form>
```

### Analytics

Add Google Analytics or other tracking:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());
    gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

### Dark Mode (Optional)

Uncomment the dark mode toggle in `script.js` and add corresponding CSS:

```css
/* Add to styles.css */
.dark-mode {
    --text-dark: #f9fafb;
    --text-light: #d1d5db;
    --bg-light: #1f2937;
    --bg-white: #111827;
    --border-color: #374151;
}
```

## 🚀 Deployment

### GitHub Pages

1. Push code to GitHub repository
2. Go to Settings → Pages
3. Select source as "Deploy from a branch"
4. Choose main branch and save

### Netlify

1. Connect your GitHub repository
2. Build settings: Leave blank for static site
3. Deploy automatically on push

### Vercel

1. Import project from GitHub
2. Framework preset: Other
3. Deploy automatically

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Modern CSS techniques and best practices

---

**Built with ❤️ using modern web technologies**
