# Personal Portfolio Website

A modern, responsive portfolio website to showcase your professional work and skills.

## Features

- Responsive design that works on all devices
- Modern and clean UI
- Smooth animations and transitions
- Contact form
- Project showcase section
- Skills display
- Mobile-friendly navigation

## Getting Started

1. Clone this repository to your local machine or download the ZIP file.
2. Customize the content in `index.html` to showcase your information:
   - Update your name, job title, and bio
   - Add your own projects with descriptions and links
   - Update your skills list
   - Add your contact information

3. Replace the avatar image:
   - The avatar image is located at `assets/avt.jpg`
   - You can replace it with your own image, keeping the same filename

4. Customize the styling (optional):
   - Change colors by editing the CSS variables in the `:root` section of `styles.css`
   - Adjust fonts, spacing, or other styling elements as desired

5. Host your website:
   - You can host this portfolio on GitHub Pages, Netlify, Vercel, or any other hosting service
   - If you're using GitHub Pages, make sure your repository is named `username.github.io`

## File Structure

- `index.html` - Main HTML file with the content and structure
- `styles.css` - CSS styling for the website
- `script.js` - JavaScript for interactivity and animations
- `assets/` - Directory for images and other assets

## Customization

### Changing Colors

To change the color scheme, edit the CSS variables in the `:root` section of `styles.css`:

```css
:root {
    --primary-color: #4a6bff; /* Main accent color */
    --secondary-color: #6c757d; /* Secondary color */
    --background-color: #f8f9fa; /* Background color */
    --text-color: #333; /* Text color */
    --light-color: #fff; /* Light color (usually white) */
    --dark-color: #212529; /* Dark color for footer, etc. */
    /* Other variables */
}
```

### Adding Projects

To add a new project, copy and paste the project card HTML structure in the projects section:

```html
<div class="project-card">
    <div class="project-image">
        <img src="path/to/project-image.jpg" alt="Project Name">
    </div>
    <div class="project-details">
        <h3>Project Name</h3>
        <p>Description of your project goes here.</p>
        <div class="project-tags">
            <span>Tag 1</span>
            <span>Tag 2</span>
            <span>Tag 3</span>
        </div>
        <div class="project-links">
            <a href="#" class="btn small-btn">View Project</a>
            <a href="#" class="btn small-btn">Source Code</a>
        </div>
    </div>
</div>
```

## Contact Form

The contact form in this template is for demonstration purposes. To make it functional, you'll need to implement server-side code or use a form submission service like Formspree or Netlify Forms.

## License

This project is open-source and available for personal or commercial use. 