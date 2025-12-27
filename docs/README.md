# Sierra Poppins Website Documentation

## Project Overview
Professional website for Sierra Poppins, a global home organizing and tidying service founded by Sierra Carrère. The site features a minimalist design with bold aesthetics, emphasizing the transformation of cluttered spaces into organized sanctuaries.

## Website Structure

### Pages
1. **Home (index.html)** - Main landing page with video hero, services overview, testimonials
2. **Services (services.html)** - Detailed service offerings and packages
3. **About (about.html)** - Sierra's story and philosophy, with subtle personal content
4. **Contact (contact.html)** - Booking form and contact information

### Key Features
- Hero video with overlay text
- Mobile-responsive design
- Smooth scrolling navigation
- Interactive contact form
- Lazy loading for images
- Animated elements on scroll

## Technical Details

### File Structure
```
website/
├── index.html          # Homepage
├── services.html       # Services page
├── about.html         # About page
├── contact.html       # Contact page
├── css/
│   ├── styles.css     # Main stylesheet
│   ├── services.css   # Services page styles
│   ├── about.css      # About page styles
│   └── contact.css    # Contact page styles
├── js/
│   └── main.js        # JavaScript functionality
├── images/            # Image assets
├── assets/            # Video and other media
└── docs/              # Documentation
```

### Technologies Used
- HTML5
- CSS3 (Custom properties, Grid, Flexbox)
- Vanilla JavaScript
- Google Fonts (Poppins, Open Sans)

### Color Palette
- Primary White: #FFFFFF
- Soft Gray: #F5F5F5
- Medium Gray: #E0E0E0
- Charcoal: #333333
- Accent Teal: #008B8B
- Accent Gold: #D4AF37

## Setup Instructions

1. **Domain & Hosting**
   - Secure domain: sierrapoppins.com
   - Set up SSL certificate
   - Configure CDN for global performance

2. **File Upload**
   - Upload all files maintaining the folder structure
   - Ensure proper permissions for all files

3. **Video Setup**
   - Add hero video file to `assets/sierra-organizing-hero.mp4`
   - Ensure video is optimized for web (compressed, proper format)
   - Add fallback image to `images/hero-fallback.jpg`

4. **Images**
   - Add Sierra's portrait to `images/sierra-portrait.jpg`
   - Optimize all images for web performance

5. **Contact Form**
   - Configure email backend for form submissions
   - Update form action in contact.html if needed
   - Test form thoroughly before launch

## Content Management

### Updating Text Content
- Homepage copy is integrated from the copywriter deck
- All text is directly embedded in HTML files
- Update meta descriptions for SEO as needed

### Adding Testimonials
New testimonials can be added to the testimonials section in index.html:
```html
<div class="testimonial-card">
    <p class="testimonial-text">"Testimonial text here"</p>
    <p class="testimonial-author">— <em>Name, Location</em></p>
</div>
```

### Service Updates
Services and pricing can be updated in services.html. Look for:
- `.service-detail-card` sections for individual services
- `.package-card` sections for packages
- Update prices in `.service-price` and `.package-price` elements

## SEO Considerations

### Meta Tags
Each page includes:
- Descriptive title tags
- Meta descriptions
- Keywords relevant to home organization

### Recommended Additions
1. Google Analytics tracking code
2. Schema markup for local business
3. XML sitemap
4. robots.txt file
5. Social media meta tags (Open Graph)

## Performance Optimization

### Current Optimizations
- Lazy loading for images
- Minification ready (CSS/JS can be minified)
- Efficient CSS with custom properties
- Mobile-first responsive design

### Recommended Enhancements
1. Compress and optimize video file
2. Implement image compression
3. Enable browser caching
4. Use a CDN for assets
5. Minify CSS and JavaScript files

## Maintenance

### Regular Updates
- Check form functionality monthly
- Update testimonials quarterly
- Review and refresh content semi-annually
- Monitor site performance metrics

### Backup Strategy
- Regular backups of all files
- Version control for major updates
- Test updates on staging environment first

## Contact Information
- **Client**: Sierra Carrère
- **Email**: SierraCarrere@gmail.com
- **Instagram**: @sierracarrere

## Future Enhancements

### Potential Additions
1. Blog section for organizing tips
2. Before/after photo gallery
3. Online scheduling integration
4. Client portal for project management
5. Newsletter signup
6. FAQ expansion

### Technical Improvements
1. Progressive Web App features
2. Advanced form validation
3. Multi-language support
4. Accessibility enhancements (ARIA labels)
5. Dark mode option

## Troubleshooting

### Common Issues
1. **Video not playing**: Check file format, ensure autoplay is muted
2. **Form not submitting**: Verify backend configuration
3. **Mobile menu issues**: Clear cache, check JavaScript console
4. **Slow loading**: Optimize media files, check hosting performance

### Browser Compatibility
Tested and compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Android)

## License & Credits
- Website developed for Sierra Poppins
- Design follows minimalist principles with bold accents
- All content © 2025 Sierra Poppins