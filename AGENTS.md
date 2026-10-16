## Development

When starting the dev server, use background mode:

```
astro dev --background
```

Manage the background server with `astro dev stop`, `astro dev status`, and `astro dev logs`.

## Documentation

Full documentation: https://docs.astro.build

Consult these guides before working on related tasks:

- [Adding pages, dynamic routes, or middleware](https://docs.astro.build/en/guides/routing/)
- [Working with Astro components](https://docs.astro.build/en/basics/astro-components/)
- [Using React, Vue, Svelte, or other framework components](https://docs.astro.build/en/guides/framework-components/)
- [Adding or managing content](https://docs.astro.build/en/guides/content-collections/)
- [Adding styles or using Tailwind](https://docs.astro.build/en/guides/styling/)
- [Supporting multiple languages](https://docs.astro.build/en/guides/internationalization/)

## Elite Property Maintenance LLC Project

This project implements a professional website for Elite Property Maintenance LLC, a veteran-owned and operated property maintenance business. The website showcases their services including lawn care, snow plowing, debris removal, car hauling, seasonal cleanup, and storm damage services.

### Brand Guidelines

**Color Palette**
- Primary: Deep Forest Green (#2d5016) - Represents reliability and growth
- Secondary: Vivid Grass Green (#7bb541) - Signifies fresh, healthy landscapes
- Accent: Black (#000000) - Bold, professional
- Neutral: White (#ffffff) - Clean, spacious
- Veteran Colors: Red (#dc2626), White (#ffffff), Blue (#1e40af) (minimal usage for veteran-owned messaging)

### Services Offered
1. Lawn Care - Mowing, trimming, and edging
2. Snow Plowing - Driveway, parking lot, and sidewalk snow removal
3. Debris Removal - Branches, brush, and yard waste
4. Car Hauling - Junk cars, non-running vehicles, local/long-distance hauling
5. Spring/Fall Cleanup - Leaf removal, brush cleanup, property cleanup
6. Storm Damage - Tree removal, debris cleanup, emergency services

### Key Features
- "From Your Lawn to Your Driveway, We Do It All!" hero section
- Prominent "Veteran Owned & Operated" messaging
- "Veterans & Seniors Discount" information (20% off for qualifying veterans and seniors)
- Phone: 989-544-0791 as primary contact
- Lead generation form for free estimates
- High-quality service imagery
- Mobile-first responsive design
- Accessible with semantic HTML

### Conversion Goals
- Generate local leads from homeowners, landlords, and property owners
- Capture phone calls and free estimate requests
- Establish premium, trustworthy brand positioning

### Technical Requirements
- Astro + Tailwind CSS 4
- Mobile-first, responsive layouts
- Semantic HTML with accessibility
- SEO optimization with local keywords
- Performance optimized loading
- Dark mode support with green-black identity

## Ongoing Development Notes

### Current Status
The project is being built using the existing Astro project structure. We have created the following components and pages:

**Core Components:**
- Header.astro - Main navigation with veteran badge
- ServiceCard.astro - Reusable service cards with hover effects
- ContactForm.astro - Lead generation form with validation
- CTA.astro - Call-to-action sections
- MobileNav.astro - Responsive mobile navigation

**Pages:**
- index.astro - Homepage with hero section and service overview
- services.astro - Services overview page
- contact.astro - Contact page with form and business information

**Configuration:**
- Updated package.json with current dependencies
- Enhanced design.md with Elite Property Maintenance branding

### Next Steps
1. Add individual service pages (lawn-care, snow-plowing, etc.)
2. Implement Footer component
3. Add SEO metadata and structured data
4. Test responsiveness across devices
5. Verify form submission functionality
6. Optimize images and performance

### Development Workflow
- Use background mode for development server
- Follow existing Astro conventions
- Ensure accessibility compliance
- Test on mobile, tablet, and desktop
- Validate form functionality
- Review SEO implementation

## Important Notes

This is a development project. Some components may need refinement, and not all pages are complete. The focus is on building a professional, high-converting website that effectively showcases Elite Property Maintenance LLC's services while highlighting their veteran-owned status and commitment to quality service.

Development is ongoing. Future enhancements will include more detailed service pages, additional trust indicators, and expanded content sections based on user feedback.
