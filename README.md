# Vikas Kumar Suthari - Portfolio Website

![Portfolio Preview](/api/placeholder/800/400)

## Overview

A modern, responsive portfolio website showcasing my skills, projects, and professional experience as a Computer Science undergraduate and AI enthusiast. This single-page application features a clean, intuitive design with smooth navigation and interactive elements.

## Features

- **Responsive Design**: Fully responsive layout that works seamlessly across desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional interface with smooth animations and transitions
- **Navigation**: Fixed navbar with smooth scrolling to different sections
- **Interactive Elements**: Hover effects and dynamic content presentation
- **Contact Form**: Integrated contact form for easy communication
- **Cross-Browser Compatible**: Tested and optimized for all modern browsers

## Sections

1. **Home**: Introduction with profile image and social links
2. **About**: Personal bio and background information
3. **Skills**: Technical skills categorized by domain
4. **Projects**: Showcase of recent projects with descriptions
5. **Education**: Academic background presented in a timeline format
6. **Experience**: Professional experience and certifications
7. **Contact**: Contact form and personal contact information

## Technologies Used

- **HTML5**: Semantic markup for structure
- **CSS3**: Custom styling with flexbox and grid layouts
- **JavaScript**: Interactive elements and smooth scrolling
- **Font Awesome**: Icon library for visual elements
- **Google Fonts**: Typography enhancement

## Setup and Deployment

### Local Development

1. Clone the repository:
   ```
   git clone https://github.com/VikasKumarSuthari/portfolio.git
   ```

2. Open the project folder:
   ```
   cd portfolio
   ```

3. Open `index.html` in your browser or use a local server:
   ```
   # Using Python's built-in server
   python -m http.server
   ```

### Deployment

The website can be deployed on any web hosting service that supports static websites:

- GitHub Pages
- Netlify
- Vercel
- Amazon S3
- Any traditional web hosting

## Customization

### Changing Colors

The color scheme can be easily modified by changing the CSS variables in the `:root` selector:

```css
:root {
    --primary-color: #3498db;
    --secondary-color: #2c3e50;
    --accent-color: #e74c3c;
    --light-color: #ecf0f1;
    --dark-color: #1a252f;
    --text-color: #333;
    --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}
```

### Adding Projects

To add new projects, duplicate the project card structure in the HTML and update the content:

```html
<div class="project-card">
    <div class="project-img">
        <i class="fas fa-icon-name"></i>
    </div>
    <div class="project-content">
        <h3 class="project-title">Project Title</h3>
        <p class="project-tech">Technologies Used</p>
        <div class="project-description">
            <p>Project description here...</p>
        </div>
        <a href="#" class="btn">View Project</a>
    </div>
</div>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Future Enhancements

- Dark/Light mode toggle
- Project filtering capabilities
- Blog section integration
- Multi-language support
- Performance optimizations for image loading

## License

© 2025 Vikas Kumar Suthari. All rights reserved.

## Contact

For any inquiries or suggestions, please reach out:

- Email: vikaskumarsuthari@gmail.com
- LinkedIn: [vikaskumar-suthari](https://linkedin.com/in/vikaskumar-suthari)
- GitHub: [VikasKumarSuthari](https://github.com/VikasKumarSuthari)
