# Claude Code Project Documentation

## Project Overview
This is a static website for a perinatal mental health psychiatrist, built with HTML, TailwindCSS, and vanilla JavaScript. The site is designed to be fully static and deployable to GitHub Pages without any build process.

## Architecture
- **Static Site**: Pure HTML/CSS/JS, no frameworks or build tools
- **Styling**: TailwindCSS via CDN
- **Form Handling**: Formspree integration for contact forms
- **Deployment**: GitHub Pages ready

## File Structure
```
/
├── index.html          # Home page with hero section
├── sobre-mi.html       # About page with biography and services
├── contacto.html       # Contact page with form
├── CLAUDE.md          # This file
└── README.md          # User documentation
```

## Key Features Implemented
- Responsive navigation with mobile hamburger menu
- Professional design with soft, warm color palette
- Contact form with Formspree integration and error handling
- SEO-friendly semantic HTML structure
- Accessibility considerations (ARIA labels, focus states)
- Cross-browser compatible CSS

## Customization Areas
The following areas require personalization:
- Doctor's name (search for `[Nombre Completo]`)
- Biography and credentials in `sobre-mi.html`
- Contact information in `contacto.html`
- Professional photo placeholder
- Formspree endpoint URL
- Social media links

## Technical Decisions
- **TailwindCSS via CDN**: No build process required, instant deployment
- **Vanilla JavaScript**: Minimal dependencies, better performance
- **Formspree**: Reliable form handling without backend
- **Semantic HTML**: Better accessibility and SEO
- **Mobile-first responsive design**: Ensures mobile compatibility

## Development Commands
Since this is a static site, no build commands are needed:
- Simply open `index.html` in a browser for local testing
- Deploy directly to GitHub Pages or any static hosting

## Testing
- Test all navigation links between pages
- Verify mobile responsiveness on different screen sizes
- Test contact form submission and validation
- Check accessibility with screen readers

## Deployment
The site is configured for GitHub Pages deployment:
1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select main branch as source
4. Site will be available at: `https://[username].github.io/[repo-name]/`

## Future Enhancements
Potential improvements that could be added:
- Blog section for articles
- Appointment booking system
- Testimonials section
- Multi-language support
- Analytics integration
- Performance optimizations

## Dependencies
- TailwindCSS (via CDN)
- Formspree (for form handling)

## Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Graceful degradation for older browsers