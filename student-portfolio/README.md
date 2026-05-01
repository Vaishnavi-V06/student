# Student Portfolio Website

A fully responsive and interactive student portfolio website built with HTML, CSS, and vanilla JavaScript.

## Features

- **Modern Design**: Clean, visually appealing interface with smooth animations
- **Dark/Light Mode**: Toggle between themes with preference saved in local storage
- **Responsive Design**: Works perfectly on mobile, tablet, and desktop devices
- **Smooth Scrolling**: Navigation with smooth scroll effects
- **Animated Elements**: Fade-in animations on scroll, typing effect, and hover effects
- **Contact Form**: Validated contact form with real-time validation
- **Loading Animation**: Professional loading screen on page load
- **Skill Bars**: Animated progress bars for skills display
- **Project Showcase**: Interactive project cards with hover effects

## Sections

1. **Home Section**: Profile photo, name, animated typing tagline, and social links
2. **About Section**: Introduction, statistics, and skills with progress bars
3. **Projects Section**: Showcase of projects with interactive cards
4. **Resume Section**: Download button for resume (PDF placeholder)
5. **Contact Section**: Contact form with validation and contact information

## File Structure

```
student-portfolio/
├── index.html      # Main HTML structure
├── style.css       # All styling and responsive design
├── script.js       # All JavaScript functionality
└── README.md       # This file
```

## How to Use

1. **Open the Website**:
   - Simply open `index.html` in your web browser
   - Or use a local server (recommended for better performance)

2. **Using a Local Server** (Optional but recommended):
   - If you have Python installed:
     ```bash
     python -m http.server 8000
     ```
   - If you have Node.js installed:
     ```bash
     npx serve
     ```
   - Then open `http://localhost:8000` in your browser

## Customization

### Personal Information

Edit the following in `index.html`:

- **Name**: Change "John Doe" to your name
- **Profile Photo**: Replace the placeholder image URL with your photo
- **Tagline Phrases**: Edit the phrases in `script.js` (typing effect)
- **About Text**: Update the about section content
- **Skills**: Modify skill names and percentages in HTML
- **Projects**: Update project information, images, and links
- **Contact Info**: Update email, phone, and location
- **Social Links**: Replace placeholder URLs with your actual social media profiles

### Colors

Edit CSS variables in `style.css`:

```css
:root {
    --primary-color: #6C63FF;    /* Main accent color */
    --secondary-color: #4CAF50;  /* Secondary accent color */
    /* ... other variables */
}
```

### Resume

Replace the placeholder link in the Resume section with your actual resume PDF file:

```html
<a href="your-resume.pdf" class="btn btn-primary" download>
    <i class="fas fa-download"></i> Download Resume
</a>
```

## Features Implementation

### Dark/Light Mode
- Theme preference is saved in localStorage
- Toggle button in the navigation bar
- Smooth transition between themes

### Animations
- Loading animation on page load
- Fade-in animations on scroll (Intersection Observer API)
- Typing effect in home section
- Hover effects on project cards and buttons
- Animated skill bars

### Form Validation
- Real-time validation on input
- Validation on form submission
- Error messages for invalid inputs
- Success message on valid submission

### Responsive Design
- Mobile-first approach
- Breakpoints at 968px (tablet), 768px (mobile), 480px (small mobile)
- Hamburger menu for mobile navigation
- Flexible grid and flexbox layouts

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS variables, Flexbox, and Grid
- **Vanilla JavaScript**: No frameworks, pure JavaScript
- **Font Awesome**: Icons (CDN)
- **Google Fonts**: Poppins font family

## Browser Compatibility

Works on all modern browsers:
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## Credits

- Font Awesome for icons: https://fontawesome.com/
- Google Fonts: https://fonts.google.com/
- Placeholder images: https://via.placeholder.com/

## License

This project is open source and available for personal and educational use.

## Tips for Beginners

1. **Start with HTML**: Understand the structure first
2. **Learn CSS**: Experiment with colors and layouts
3. **JavaScript**: Add interactivity step by step
4. **Test frequently**: Check your changes in the browser
5. **Use browser dev tools**: Inspect elements and debug
6. **Comment your code**: Add comments for clarity

## Future Enhancements

- Add more project examples
- Include testimonials section
- Add blog section
- Implement contact form backend
- Add more animations and transitions
- Include a timeline for education/experience

---

**Happy Coding! 🚀**
