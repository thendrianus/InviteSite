# Natal Batam 2025 - Christmas Invitation Website

## Project Overview

An elegant, single-page invitation website for the Christmas event "Natal Batam 2025 - Tidak Ada yang Mustahil" (Nothing is Impossible). Designed in the style of a wedding invitation with a starry night background, gold accents, and elegant typography.

**Status:** Production-ready  
**Date Created:** November 19, 2025  
**Technology:** Pure HTML5, CSS3, Vanilla JavaScript (single file)

## Key Features

1. **Starry Night Background** - CSS-generated stars with midnight blue gradient matching the event brochure
2. **Dynamic URL Personalization** - Supports 4 parameter cases: to+from, to only, from only, neither
3. **Mobile-First Responsive Design** - Optimized for all screen sizes with center-oriented layout
4. **RSVP Form** - Async form submission with success/error feedback
5. **Background Music** - Christmas music with floating play/pause control
6. **Elegant Animations** - Fade-in effects, smooth scrolling, hover interactions

## Project Structure

```
.
├── index.html          # Main website file (single-file implementation)
├── README.md           # User documentation and setup instructions
├── .gitignore         # Git ignore patterns for Python and Replit
└── attached_assets/    # Original design assets
    ├── 16 9 E-Flyer Natal Batam 2025_1763516600105.jpg
    └── Pasted-You-are-an-expert-frontend-developer...txt
```

## Configuration

### RSVP Form Setup (Required for Production)

The website is ready to use, but to enable RSVP submissions:

1. Create a free Formspree account at https://formspree.io
2. Create a new form and obtain the form ID
3. Edit `index.html` line 544 and replace `YOUR_FORM_ID` with the actual ID
4. Test the form submission to verify it works

### URL Personalization Examples

- Default: `index.html`
- With recipient: `index.html?to=John+Doe`
- With sender: `index.html?from=Maria`
- Both: `index.html?to=John+Doe&from=Maria`

## Event Details

- **Event:** Ibadah Natal Batam (Christmas Service)
- **Theme:** Tidak Ada yang Mustahil (Nothing is Impossible)
- **Speaker:** Pdt. Eko Aria, M.Th.
- **Date:** Saturday, December 6, 2025
- **Time:** 6:30 PM WIB
- **Venue:** Batam Reformed Centre, Jl. Reformasi No. 3, Batam Center
- **Contact:** 0811-7007-0800

## Technical Specifications

- **Single HTML file:** All styles and scripts inline
- **No dependencies:** No external libraries or frameworks
- **Fonts:** Google Fonts (Great Vibes, Cormorant Garamond, Montserrat)
- **Browser Support:** All modern browsers (Chrome, Firefox, Safari, Edge)
- **Mobile Optimized:** Touch-friendly buttons, responsive layout, mobile-first CSS

## Architecture

### Section Structure

1. **Hero Section** - Full-height starry background with personalized greeting
2. **Greeting Section** - White background with invitation message
3. **Details Section** - Dark background with event information and map link
4. **RSVP Section** - White background with form for attendance confirmation

### Form Handling

- Async/await fetch API for submission
- Client-side validation for attendance/status consistency
- Loading state during submission
- Success/error message feedback with auto-hide
- Graceful error handling with user-friendly messages

### Personalization Logic

JavaScript reads URL parameters and updates:
- Guest name display
- Sender information visibility
- RSVP form pre-fill (name field)

All 4 parameter cases handled correctly as specified.

## Recent Changes

**November 19, 2025:**
- Initial implementation with all MVP features
- Added async form submission with proper error handling
- Implemented success/error feedback messages
- Created comprehensive documentation (README.md)
- Added setup instructions in HTML comments
- Created .gitignore for Python/Replit environment
- **Integrated actual artwork:** Used "Background Malaikat Maria" image as hero background with angel and Mary painting
- **Added decorative element:** Placed angel/Mary painting in greeting section for enhanced visual appeal
- **Enhanced design:** Combined real starry background image with CSS-generated stars for depth

## Next Steps for Production

1. **Configure Formspree** - Replace placeholder form ID with actual endpoint
2. **Test Form Submission** - Verify end-to-end RSVP delivery
3. **Device Testing** - Test on actual mobile devices and different browsers
4. **Optional:** Replace placeholder audio URL with actual Christmas music file
5. **Deploy** - Use Replit publish feature or host on custom domain

## Customization Guide

### Colors
- Gold accent: `#d4af37`
- Midnight blue: `#0a1628`
- Background gradient: `#0a1628` to `#1a2642`

### Fonts
- Title/Cursive: Great Vibes
- Serif: Cormorant Garamond
- Sans-serif: Montserrat

### Stars
- Count: 150 stars (line 625 in JavaScript)
- Color: White and gold (20% gold stars)
- Animation: Subtle twinkle effect (3s duration)

## User Preferences

None specified yet - this is a new project.
