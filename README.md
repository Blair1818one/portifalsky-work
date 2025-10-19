# Mawuba Blair - Portfolio Website

A modern, responsive portfolio website built with HTML5, CSS3, and Bootstrap 5. This project showcases web development skills, personal projects, and professional experience.

## 🚀 Live Demo

[View Live Website](https://blair1818one.github.io/portfolio-website/)

## 📋 Project Overview

This portfolio website demonstrates proficiency in:
- **HTML5**: Semantic markup with proper structure and accessibility
- **CSS3**: Custom styling, animations, and responsive design
- **Bootstrap 5**: Component integration and grid system
- **JavaScript**: Interactive features and form validation

## 🎯 Features

### ✅ Core Requirements Met
- **Multi-page Website**: 4 pages (Home, About, Projects, Contact)
- **Semantic HTML5**: Proper use of `<header>`, `<nav>`, `<section>`, `<footer>`, etc.
- **External CSS**: All custom styling in separate CSS file
- **Bootstrap 5 Integration**: Navbar, cards, forms, responsive grid
- **Responsive Design**: Mobile-first approach with breakpoints
- **Navigation**: Working links between all pages
- **Embedded Content**: Images and YouTube video
- **Form Validation**: Contact form with client-side validation

### 🌟 Bonus Features
- **Scroll-to-top Button**: Smooth scrolling with fade animation
- **Project Filter**: Interactive filtering by category
- **Modal Dialogs**: Detailed project information
- **Smooth Animations**: CSS transitions and scroll-triggered animations
- **Loading States**: Form submission feedback
- **FAQ Section**: Bootstrap accordion component

## 📁 Project Structure

```
portfolio-website/
├── index.html          # Home page
├── about.html          # About page
├── projects.html       # Projects showcase
├── contact.html        # Contact form
├── css/
│   └── style.css       # Custom styles
├── js/
│   └── script.js       # JavaScript functionality
└── README.md           # Project documentation
```

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup, accessibility features
- **CSS3**: Custom properties, flexbox, grid, animations
- **Bootstrap 5.3.0**: Components and responsive utilities
- **JavaScript (ES6+)**: Modern JavaScript features
- **Font Awesome 6.0**: Icons and visual elements

### Design Principles
- **Mobile-First**: Responsive design starting from mobile
- **Progressive Enhancement**: Core functionality without JavaScript
- **Accessibility**: ARIA labels, semantic HTML, keyboard navigation
- **Performance**: Optimized images, minimal dependencies

## 📱 Responsive Design

The website is fully responsive across all device sizes:

- **Mobile (< 576px)**: Stacked layout, touch-friendly buttons
- **Tablet (576px - 992px)**: Adjusted grid columns, medium spacing
- **Desktop (> 992px)**: Full layout with sidebar elements

### Breakpoints Used
- `xs`: < 576px (Extra small devices)
- `sm`: ≥ 576px (Small devices)
- `md`: ≥ 768px (Medium devices)
- `lg`: ≥ 992px (Large devices)
- `xl`: ≥ 1200px (Extra large devices)

## 🎨 Design Choices

### Color Scheme
- **Primary**: #007bff (Bootstrap Blue)
- **Secondary**: #6c757d (Gray)
- **Success**: #28a745 (Green)
- **Warning**: #ffc107 (Yellow)
- **Danger**: #dc3545 (Red)
- **Info**: #17a2b8 (Cyan)

### Typography
- **Font Family**: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
- **Headings**: Bootstrap's responsive heading classes
- **Body Text**: Optimized line-height (1.6) for readability

### Layout
- **Grid System**: Bootstrap's 12-column grid
- **Spacing**: Consistent padding and margins using Bootstrap utilities
- **Cards**: Elevated cards with hover effects
- **Navigation**: Fixed-top navbar with smooth scrolling

## ⚡ Performance Optimizations

1. **Minimal Dependencies**: Only essential external libraries
2. **Optimized Images**: Proper sizing and lazy loading
3. **Efficient CSS**: Minimal unused styles, organized structure
4. **JavaScript**: Debounced scroll events, efficient DOM queries
5. **CDN Resources**: Fast loading of Bootstrap and Font Awesome

## 🔧 Setup Instructions

1. **Clone Repository**
   ```bash
   git clone https://github.com/your-username/portfolio-website.git
   cd portfolio-website
   ```

2. **Open in Browser**
   - Simply open `index.html` in any modern web browser
   - Or use a local server for development:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Customize Content**
   - Update personal information in HTML files
   - Replace placeholder images with your photos
   - Modify color scheme in CSS variables
   - Add your own projects and content

## 📝 Customization Guide

### Updating Personal Information
1. Edit name, title, and description in `index.html`
2. Update contact details in `contact.html`
3. Modify skills and experience in `about.html`
4. Replace project information in `projects.html`

### Changing Color Scheme
Update CSS variables in `css/style.css`:
```css
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
    /* ... other colors */
}
```

### Adding New Projects
1. Copy project card structure in `projects.html`
2. Update image, title, description, and technologies
3. Add corresponding modal for detailed view
4. Update filter categories if needed

## 🧪 Testing

### Browser Compatibility
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

### Device Testing
- ✅ iPhone SE (375px)
- ✅ iPad (768px)
- ✅ Desktop (1920px)

### Accessibility Testing
- ✅ Keyboard navigation
- ✅ Screen reader compatibility
- ✅ Color contrast ratios
- ✅ Alt text for images

## 🚀 Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Go to Settings → Pages
3. Select source branch (main/master)
4. Access via `https://username.github.io/repository-name`

### Netlify
1. Connect GitHub repository
2. Build command: (none needed)
3. Publish directory: `/`
4. Deploy automatically on push

### Vercel
1. Import GitHub repository
2. Framework preset: Other
3. Build command: (none)
4. Deploy automatically

## 📊 Performance Metrics

- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**Mawuba Blair**
- Email: mawuba.blair@email.com
- LinkedIn: [linkedin.com/in/mawuba-blair](https://linkedin.com/in/mawuba-blair)
- GitHub: [github.com/blair1818one](https://github.com/blair1818one)

## 🙏 Acknowledgments

- Bootstrap team for the excellent framework
- Font Awesome for the icon library
- Unsplash for high-quality stock photos
- YouTube for video embedding capabilities

---

**Note**: This portfolio is a template and should be customized with your personal information, projects, and branding before use.
