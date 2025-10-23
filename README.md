# Poonkuzhali S - Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML5, CSS3, and JavaScript. Showcasing my skills as a B.Tech Information Technology student, my projects, and professional development journey.

## Features

- **Responsive Design**: Looks great on all devices (desktop, tablet, mobile)
- **Modern UI**: Clean, professional design with smooth animations
- **Smooth Scrolling**: Navigation with smooth scrolling between sections
- **Interactive Elements**: Hover effects, form validation, and scroll animations
- **Fast Loading**: Optimized for performance with external CDN resources
- **SEO Friendly**: Proper HTML structure and meta tags

## Sections

1. **Hero/Home**: Eye-catching introduction with call-to-action buttons
2. **About Me**: Personal introduction, skills showcase, and statistics
3. **Projects**: Featured projects with descriptions and technology tags
4. **Contact**: Contact form and social media links

## Getting Started

### 1. Personalization

✅ **Already Personalized with Poonkuzhali's Information:**

#### Current Content Includes:
- **Name**: Poonkuzhali S
- **Title**: B.Tech Information Technology Student & Web Developer  
- **Education**: Christ College Of Engineering And Technology
- **Skills**: Java, C/C++, Web Development, AI/ML, Team Collaboration, Communication
- **Featured Project**: AI-based Accident Detection App
- **Contact**: poonkuzhaliss.am24@gmail.com, +91 99529 15327
- **Location**: Nilakkal, Pudukkotai - 605009
- **LinkedIn**: Connected to actual profile

#### To Further Customize:
- Add your actual photo to replace the placeholder
- Update project links when available
- Add more projects as you complete them

### 2. Adding Your Photo

Replace the placeholder profile image:
1. Add your photo to the `images` folder
2. In `index.html`, replace the placeholder div with an img tag:

```html
<!-- Replace this -->
<div class="image-placeholder">
    <i class="fas fa-user-circle"></i>
</div>

<!-- With your photo -->
<img src="images/poonkuzhali-photo.jpg" alt="Poonkuzhali S" class="profile-image">
```

### 3. Project Images

Add screenshots of your projects:
1. Create an `images` folder in your project directory
2. Add project screenshots
3. Replace the placeholder divs in the project cards:

```html
<!-- Replace this -->
<div class="project-placeholder">
    <i class="fas fa-globe"></i>
</div>

<!-- With your project image -->
<img src="images/project1.jpg" alt="Project Name">
```

### 4. Customizing Colors

The main colors are defined in `styles.css`. Key color variables:
- Primary blue: `#2563eb`
- Accent yellow: `#fbbf24`
- Dark text: `#1e293b`
- Light text: `#64748b`

### 5. Adding More Projects

To add more projects, copy the project card structure:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder">
            <i class="fas fa-code"></i>
        </div>
        <div class="project-overlay">
            <a href="your-live-demo-link" class="project-link"><i class="fas fa-external-link-alt"></i></a>
            <a href="your-github-link" class="project-link"><i class="fab fa-github"></i></a>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Your project description goes here.</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
    </div>
</div>
```

## File Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── images/            # (Create this folder for your images)
    ├── profile.jpg
    ├── project1.jpg
    └── project2.jpg
```

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality and smooth scrolling
- **Font Awesome**: Icons for social links and UI elements
- **Google Fonts**: Inter font family for typography

## Browser Support

This portfolio works on all modern browsers:
- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## Deployment

You can deploy this portfolio to any web hosting service:

### GitHub Pages (Free)
1. Create a GitHub repository
2. Upload your files
3. Go to Settings > Pages
4. Select source branch
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify (Free)
1. Drag and drop your project folder to Netlify
2. Your site will be live instantly with a custom URL

### Other Hosting Options
- Vercel
- Firebase Hosting
- Traditional web hosting services

## Customization Tips

1. **Fonts**: Change the font family by updating the Google Fonts link and CSS
2. **Animations**: Modify transition durations in CSS for faster/slower animations
3. **Layout**: Adjust grid layouts and spacing in the CSS
4. **Colors**: Create a consistent color scheme by updating the color values
5. **Content**: Add more sections by copying existing section structures

## Contact Form

The contact form includes basic client-side validation. For a fully functional form, you'll need to:
1. Set up a backend service (Node.js, PHP, etc.)
2. Or use a service like Formspree, Netlify Forms, or EmailJS

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio:
1. Check the comments in the code files
2. Refer to this README
3. Search for specific CSS/JavaScript tutorials online

---

**Happy coding!** 🚀
