# Natal Batam 2025 - Invitation Website

An elegant, wedding-style single-page invitation website for the Christmas event "Tidak Ada yang Mustahil" (Nothing is Impossible).

## Features

- ✨ **Starry Night Background** - Beautiful CSS-generated stars with midnight blue gradient
- 💌 **Dynamic Personalization** - Customize greetings via URL parameters
- 📱 **Mobile-First Design** - Fully responsive and optimized for all devices
- 🎵 **Background Music** - Christmas music with floating play/pause control
- 📝 **RSVP Form** - Elegant form for attendance confirmation
- 🎨 **Wedding-Inspired Design** - Gold accents, elegant typography, and centered layout

## How to Use

### Basic Usage

Simply open `index.html` in a web browser. The website works perfectly as-is with default greetings.

### Personalized Invitations

Create personalized invitation links using URL parameters:

1. **With recipient and sender:**
   ```
   index.html?to=John+Doe&from=Maria
   ```
   Shows: "Bapak/Ibu/Sdr/i John Doe" and "Undangan ini dikirim oleh: Maria"

2. **With recipient only:**
   ```
   index.html?to=John+Doe
   ```
   Shows: "Bapak/Ibu/Sdr/i John Doe"

3. **With sender only:**
   ```
   index.html?from=Maria
   ```
   Shows: "Saudara/i terkasih" and "Undangan ini dikirim oleh: Maria"

4. **Default (no parameters):**
   ```
   index.html
   ```
   Shows: "Saudara/i terkasih"

### Setting Up RSVP Form

To enable RSVP submissions:

1. **Using Formspree (Recommended - Free):**
   - Go to [formspree.io](https://formspree.io)
   - Create a free account
   - Create a new form
   - Copy your form ID (e.g., `xwkagpqr`)
   - Open `index.html` and find line 544
   - Replace `YOUR_FORM_ID` with your actual ID:
     ```html
     <form action="https://formspree.io/f/xwkagpqr" method="POST" id="rsvpForm">
     ```

2. **Alternative Services:**
   - Google Forms with custom script
   - Netlify Forms
   - Basin
   - Your own backend API

## Event Details

- **Speaker:** Pdt. Eko Aria, M.Th.
- **Date:** Saturday, December 6, 2025
- **Time:** 6:30 PM WIB
- **Location:** Batam Reformed Centre, Jl. Reformasi No. 3, Batam Center
- **Contact:** 0811-7007-0800

## Technical Details

- **Single File:** Everything in one `index.html` file
- **No Dependencies:** No external libraries or frameworks
- **Google Fonts:** Great Vibes (cursive), Cormorant Garamond (serif), Montserrat (sans-serif)
- **Pure Vanilla:** HTML5 + CSS3 + JavaScript

## Customization

To customize the website, edit `index.html`:

- **Colors:** Search for `#d4af37` (gold) and `#0a1628` (midnight blue)
- **Event Details:** Update section starting at line 490
- **Text Content:** Modify the greeting and intro sections
- **Stars Count:** Change `starCount` variable (line 625)

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

Free to use and customize for your event needs.
