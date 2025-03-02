# Eric's Professional Business Website

A modern, responsive personal website for Eric, showcasing his professional experience and expertise.

## Features

- Responsive design that works on all devices
- Modern and clean user interface
- Smooth scrolling navigation
- Interactive portfolio section
- Contact form with validation
- Social media integration
- Animated sections for engaging user experience

## Structure

```
eric-business-website/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
└── images/
    ├── hero-bg.jpg
    ├── project1.jpg
    ├── project2.jpg
    └── project3.jpg
```

## Setup Instructions

1. Add your images to the `images/` directory:
   - Add a hero background image named `hero-bg.jpg`
   - Add portfolio images named `project1.jpg`, `project2.jpg`, and `project3.jpg`

2. Customize the content:
   - Update the contact information in `index.html`
   - Modify the portfolio projects in `index.html`
   - Update social media links in the footer

3. Deploy:
   - Upload all files to your web hosting service
   - Ensure all files maintain their relative directory structure

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Poppins)

## Customization

### Colors
The main color scheme can be modified in `css/style.css`:
- Primary Color: #3498db
- Secondary Color: #2c3e50
- Background Color: #f9f9f9

### Typography
The website uses 'Poppins' as the main font family. To change this:
1. Update the Google Fonts link in `index.html`
2. Modify the font-family in `css/style.css`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contact Form Integration

The contact form is currently set up to log to the console. To make it functional:
1. Set up a backend server to handle form submissions
2. Update the form handling code in `js/main.js`
3. Add appropriate error handling and success messages

## Maintenance

Regular updates recommended for:
- Security patches
- Browser compatibility
- Content updates
- Image optimization
