# Sierra Poppins Website - Quick Start Guide

## Viewing the Website Locally

1. **Open the website**
   - Navigate to the `website` folder
   - Double-click on `index.html` to open in your browser
   - Or right-click and select "Open with" your preferred browser

2. **Navigate between pages**
   - Use the navigation menu to explore all pages
   - All links are relative and will work locally

## Essential Files to Add

Before going live, you need to add these media files:

### 1. Hero Video
- **Location**: `website/assets/sierra-organizing-hero.mp4`
- **Requirements**: MP4 format, web-optimized, under 10MB recommended
- **Content**: Sierra organizing a space or time-lapse of transformation

### 2. Hero Fallback Image  
- **Location**: `website/images/hero-fallback.jpg`
- **Requirements**: JPEG format, 1920x1080px recommended
- **Purpose**: Displays if video fails to load

### 3. Sierra's Portrait
- **Location**: `website/images/sierra-portrait.jpg`
- **Requirements**: JPEG format, at least 600x600px
- **Usage**: About page profile image

## Quick Edits

### Updating Contact Email
1. Open any HTML file
2. Find: `SierraCarrere@gmail.com`
3. Replace with new email address
4. Repeat for all HTML files

### Changing Prices
1. Open `services.html`
2. Look for elements with class `service-price` or `package-price`
3. Update the price text
4. Save the file

### Adding a Testimonial
1. Open `index.html`
2. Find the testimonials section
3. Copy an existing testimonial card
4. Update the text and author name
5. Save the file

### Updating Colors
1. Open `css/styles.css`
2. Find the `:root` section at the top
3. Update color values:
   - `--accent-teal: #008B8B;` (change hex code)
   - `--accent-gold: #D4AF37;` (change hex code)
4. Save - colors update site-wide!

## Form Setup

The contact form requires backend configuration to actually send emails. Options:

1. **Simple Solution**: Use a service like Formspree
   - Sign up at formspree.io
   - Get your form endpoint
   - Add to contact form: `action="https://formspree.io/f/YOUR-FORM-ID"`

2. **Advanced Solution**: Custom backend
   - Requires server-side programming
   - More control over form handling

## Testing Checklist

Before launching, test these key features:

- [ ] All navigation links work
- [ ] Mobile menu opens/closes properly
- [ ] Video plays (once added)
- [ ] Images load (once added)
- [ ] Contact form displays correctly
- [ ] Site looks good on mobile devices
- [ ] Text is readable and properly formatted

## Next Steps

1. **Add missing media files** (video, images)
2. **Configure hosting** and domain
3. **Set up form handling**
4. **Test thoroughly** on different devices
5. **Launch!** 🚀

## Need Help?

- Check the full documentation in `docs/README.md`
- Review the deployment checklist in `docs/deployment-checklist.md`
- Contact Sierra at SierraCarrere@gmail.com for content questions