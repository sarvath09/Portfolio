# Sarvath Kounein - Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript for Sarvath Kounein, a Computer Science student specializing in Artificial Intelligence and Machine Learning.

## 🌟 Features

### Design & Layout
- **Modern & Clean Design**: Minimalist design with professional aesthetics
- **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- **Smooth Animations**: Subtle hover effects and scroll animations
- **Professional Typography**: Uses Inter font family for excellent readability
- **Color Scheme**: Professional blue and purple gradient theme

### Sections Included
1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About Me**: Personal introduction with statistics
3. **Skills**: Categorized skills with icons and hover effects
4. **Projects**: Two featured projects with detailed descriptions
5. **Education**: Academic background and achievements
6. **Certifications**: Professional certifications and achievements
7. **Contact**: Contact information and contact form

### Technical Features
- **Fixed Navigation**: Sticky navbar with smooth scrolling
- **Mobile Menu**: Hamburger menu for mobile devices
- **Form Validation**: Contact form with client-side validation
- **Dynamic Year**: Automatically updates copyright year
- **Scroll-to-Top**: Convenient back-to-top button
- **Loading Animation**: Smooth page load transition

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server required - runs entirely in the browser

### Installation
1. Download or clone the repository
2. Open `index.html` in your web browser
3. The website will load immediately with all features working

### File Structure
```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md          # This documentation file
```

## 🎨 Customization

### Personal Information
Update the following in `index.html`:

#### Contact Information
```html
<!-- Update these sections with your actual information -->
<a href="mailto:sarvathkounein9@gmail.com">sarvathkounein9@gmail.com</a>
<a href="tel:+918310333721">+91 8310333721</a>
<p>Chamrajpet, Chickballapur-562101, Karnataka, India</p>
<a href="https://www.linkedin.com/in/sarvath-kounein-05043527b">Sarvath Kounein</a>
```

#### Projects
```html
<!-- Update project descriptions and links -->
<div class="project-card">
    <h3>Your Project Name</h3>
    <p>Your project description...</p>
    <div class="project-tech">
        <span class="tech-tag">Technology Used</span>
    </div>
    <div class="project-links">
        <a href="your-demo-link" class="project-link">Live Demo</a>
        <a href="your-github-link" class="project-link">Code</a>
    </div>
</div>
```

#### Skills
```html
<!-- Update skills in the skills section -->
<div class="skill-items">
    <span class="skill-tag">Your Skill</span>
    <!-- Add more skills as needed -->
</div>
```

### Styling Customization

#### Colors
Update the color scheme in `styles.css`:
```css
/* Primary colors */
--primary-color: #2563eb;
--secondary-color: #7c3aed;
--accent-color: #fbbf24;

/* Background colors */
--bg-primary: #fafafa;
--bg-secondary: #f8fafc;
```

#### Fonts
Change the font family in `styles.css`:
```css
body {
    font-family: 'Your-Font', sans-serif;
}
```

## 📱 Responsive Design

The website is fully responsive with breakpoints at:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

### Performance Features
- Optimized images and icons
- Minimal JavaScript footprint
- Efficient CSS animations
- Fast loading times

## 📝 Contact Form

The contact form includes:
- **Client-side validation**: Ensures all fields are filled
- **Email validation**: Checks for valid email format
- **Form reset**: Clears form after successful submission
- **User feedback**: Shows confirmation message

**Note**: The form currently shows a success message. To make it functional, you'll need to:
1. Set up a backend server
2. Configure email sending functionality
3. Update the form action in `script.js`

## 🎯 SEO & Accessibility

### SEO Features
- Semantic HTML structure
- Meta tags for social sharing
- Proper heading hierarchy
- Alt text for images (when added)

### Accessibility Features
- Keyboard navigation support
- Screen reader friendly
- High contrast ratios
- Focus indicators

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop the project folder to Netlify
2. Your site will be deployed instantly
3. Get a custom domain if needed

### Vercel
1. Connect your GitHub repository to Vercel
2. Deploy automatically on every push
3. Get a custom domain and SSL certificate

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📞 Support

If you have any questions or need help customizing the portfolio, please reach out!

---

**Built with ❤️ for showcasing professional portfolios**

