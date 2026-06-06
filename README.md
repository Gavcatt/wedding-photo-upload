# Gavin & Jessica | Digital Wedding Invitation

A bespoke, email-ready wedding invitation page with an animated envelope reveal, placeholders for personal images, and an elegant story section. It is styled to match the aesthetic of your wedding photo drop landing page while focusing on a premium invitation experience.

## What it includes

- `index.html` — animated envelope invitation with the wedding date, venue, and guest greeting placeholder
- `styles.css` — elegant, responsive layout with soft gradients and premium typography
- `script.js` — personalized greeting support and envelope open animation

## How to use

1. Host the folder on any static site provider (GitHub Pages, Netlify, Vercel, etc.).
2. Share the deployed page URL by email or message.
3. Personalize the greeting by appending `?guest=First+Name` to the link.

Example:

`https://your-domain.com/?guest=Emma`

## Customization

- Replace the RSVP email in `index.html` with your preferred contact address.
- Update the story section copy to include your own wedding story details.
- Replace the placeholder photo cards with real images or image URLs if desired.

## Deployment

- GitHub Pages:
  1. Create a new GitHub repository and push these files.
  2. In the repo settings, enable GitHub Pages from the `main` branch and root folder.
  3. Use the provided site URL to share the invitation.
- Netlify/Vercel: connect the repo and deploy the folder as a static site.

## RSVP page

This project now includes `rsvp.html`, which provides a guest response form for attendance, guests, dietary preferences, and a message for the couple.

- The form stores RSVP data locally in the browser.
- To enable live email delivery, replace `https://formsubmit.co/your-email@example.com` in `rsvp.html` with your own FormSubmit email endpoint or backend endpoint.
