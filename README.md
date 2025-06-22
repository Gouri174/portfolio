# ML Professional Portfolio Website

A modern, responsive portfolio website designed specifically for Machine Learning professionals. Features a beautiful glassmorphism design with smooth animations and professional layouts.

## 🌟 Features

### Core Features
- **Single Page Design**: One-page scrollable website with smooth navigation
- **Professional Header**: Fixed navigation with smooth scrolling to sections
- **Hero Section**: Prominent display of name, title, and professional image
- **About Section**: Professional background and technical skills
- **Experience Timeline**: Visual timeline of work experience
- **Projects Showcase**: Portfolio projects with dashboard images and links
- **Articles Section**: Published papers and articles with clickable links
- **Testimonials**: Client and professor feedback
- **Contact Section**: Professional contact information with social links

### Design Features
- **Glassmorphism Effects**: Modern frosted glass design with backdrop blur
- **Responsive Design**: Optimized for all devices (desktop, tablet, mobile)
- **Smooth Animations**: Hover effects, scroll animations, and transitions
- **Modern UI**: Professional card layouts with shadows and hover states
- **Gradient Backgrounds**: Beautiful color schemes and visual appeal

### Technical Features
- **Smooth Scrolling**: Navigation between sections
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Scroll Animations**: Elements animate as they come into view
- **Active Navigation**: Highlights current section in navigation
- **Performance Optimized**: Throttled scroll events and efficient animations

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation
1. Clone or download the project files
2. Open `index.html` in your web browser
3. The website should load immediately with all features working

### File Structure
```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Customization

### Personal Information
Edit the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-name">Your Name</h1>
<h2 class="hero-title">Your Professional Title</h2>
<p class="hero-description">Your professional description</p>
```

#### About Section
```html
<p>Your professional background and experience</p>
<div class="skill-tags">
    <span class="skill-tag">Your Skill 1</span>
    <span class="skill-tag">Your Skill 2</span>
    <!-- Add more skills -->
</div>
```

#### Experience
```html
<div class="timeline-item">
    <div class="timeline-content">
        <h3>Your Job Title</h3>
        <h4>Company Name</h4>
        <p class="timeline-date">Date Range</p>
        <p>Job description and achievements</p>
    </div>
</div>
```

#### Projects
```html
<div class="project-card">
    <div class="project-image">
        <!-- Add your project dashboard image here -->
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-demo-link" class="project-link">Live Demo</a>
            <a href="your-github-link" class="project-link">GitHub</a>
        </div>
    </div>
</div>
```

#### Articles
```html
<article class="article-card">
    <div class="article-image">
        <!-- Add your article image here -->
    </div>
    <div class="article-content">
        <h3>Article Title</h3>
        <p>Publication details</p>
        <span class="article-date">Publication Date</span>
        <a href="article-link" class="article-link">Read Article</a>
    </div>
</article>
```

#### Testimonials
```html
<div class="testimonial-card">
    <div class="testimonial-content">
        <p>"Testimonial text"</p>
        <div class="testimonial-author">
            <h4>Author Name</h4>
            <span>Author Title/Company</span>
        </div>
    </div>
</div>
```

#### Contact Information
```html
<a href="mailto:your-email@example.com" class="contact-link">
    <i class="fas fa-envelope"></i>
    <span>your-email@example.com</span>
</a>
<a href="your-linkedin-profile" class="contact-link" target="_blank">
    <i class="fab fa-linkedin"></i>
    <span>LinkedIn</span>
</a>
<a href="your-github-profile" class="contact-link" target="_blank">
    <i class="fab fa-github"></i>
    <span>GitHub</span>
</a>
```

### Styling Customization

#### Color Scheme
Edit the CSS variables in `styles.css`:
```css
/* Primary colors */
--primary-color: #ffd700;
--secondary-color: #ffed4e;
--background-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

#### Fonts
Change the font family in `styles.css`:
```css
body {
    font-family: 'Your-Font', sans-serif;
}
```

#### Animations
Adjust animation speeds and effects in `script.js`:
```javascript
// Typing animation speed
typeWriter(heroName, originalText, 150); // Adjust the last number

// Scroll animation threshold
const observerOptions = {
    threshold: 0.1, // Adjust this value
    rootMargin: '0px 0px -50px 0px'
};
```

## 📱 Responsive Design

The website is fully responsive and optimized for:
- **Desktop**: Full layout with side-by-side content
- **Tablet**: Adjusted grid layouts and spacing
- **Mobile**: Single column layout with hamburger navigation

### Breakpoints
- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px

## 🎯 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to Netlify
2. Your site will be deployed automatically
3. Custom domain can be added in settings

### Vercel
1. Connect your GitHub repository to Vercel
2. Deploy automatically on every push
3. Custom domain support available

## 🔧 Advanced Customization

### Adding Images
1. Replace placeholder divs with actual images:
```html
<div class="hero-image">
    <img src="path/to/your/image.jpg" alt="Your Name" class="profile-image">
</div>
```

2. Add corresponding CSS:
```css
.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 2px solid rgba(255, 255, 255, 0.2);
}
```

### Adding More Sections
1. Add new section in HTML:
```html
<section id="new-section" class="new-section">
    <div class="container">
        <h2 class="section-title">New Section</h2>
        <!-- Your content -->
    </div>
</section>
```

2. Add navigation link:
```html
<li><a href="#new-section" class="nav-link">New Section</a></li>
```

3. Add CSS styling for the new section.

## 📞 Support

For questions or customization help:
- Check the code comments for guidance
- Review the CSS classes for styling options
- Modify the JavaScript for behavior changes

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Modern CSS techniques and glassmorphism design
- Intersection Observer API for scroll animations

---

**Happy coding! 🚀** 