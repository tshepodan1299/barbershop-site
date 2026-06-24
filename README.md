# Elite Cuts Barbershop Website

A modern, professional barbershop website for Elite Cuts in Gaborone, Botswana.

## Features

✨ **Responsive Design**
- Mobile-friendly interface
- Tablet and desktop optimization
- Touch-friendly navigation

🎨 **Professional Styling**
- Modern dark theme with gold accents
- Smooth animations and transitions
- Interactive hover effects

📋 **Key Sections**
- **Home** - Eye-catching hero section with call-to-action
- **Services** - Comprehensive service catalog with pricing
- **About** - Company history and statistics
- **Team** - Meet the professional barbers
- **Gallery** - Portfolio of work
- **Booking** - Easy appointment scheduling
- **Contact** - Multiple ways to get in touch

🔧 **Functionality**
- Appointment booking system with local storage
- Contact form for inquiries
- WhatsApp integration
- Smooth scrolling navigation
- Mobile hamburger menu

## File Structure

```
barbershop-site/
├── index.html      # Main HTML file
├── styles.css      # Stylesheet
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Setup Instructions

1. Clone or download the repository
2. Open `index.html` in a web browser
3. No server or additional dependencies required

## Customization

### Update Contact Information
Edit the contact details in `index.html`:
- Phone numbers (currently masked)
- WhatsApp link
- Business hours
- Location

### Add Your Images
Replace placeholder images by:
1. Adding image files to the repository
2. Updating image paths in `index.html`
3. Modifying the `.placeholder-image` and `.gallery-placeholder` CSS if needed

### Modify Colors
Change the color scheme in `styles.css`:
```css
:root {
    --primary-color: #d4af37;        /* Gold accent */
    --dark-color: #0f0f0f;           /* Dark background */
    --darker-color: #000;            /* Black background */
    --accent-color: #c41e3a;         /* Red accent */
}
```

### Update Services
Edit the services section in `index.html` with your offerings and pricing.

## Data Storage

- **Bookings**: Stored in browser's localStorage under `eliteCutsBookings`
- **Contact Messages**: Stored in browser's localStorage under `eliteCutsMessages`

To view stored data in browser console:
```javascript
JSON.parse(localStorage.getItem('eliteCutsBookings'))
JSON.parse(localStorage.getItem('eliteCutsMessages'))
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Optimized CSS and JavaScript
- Smooth animations and transitions
- Responsive images and icons
- Fast loading time

## Future Enhancements

- Backend integration for booking confirmation emails
- Online payment system
- Photo gallery with real images
- Customer testimonials/reviews
- Blog section
- Social media integration
- SMS notifications

## Credits

Built with modern web technologies:
- HTML5
- CSS3
- Vanilla JavaScript
- Font Awesome Icons

## License

© 2026 Elite Cuts Barbershop. All rights reserved.

---

For more information or to book an appointment, visit the website or contact us directly!
