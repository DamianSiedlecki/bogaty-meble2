
# Agent Guidelines

These instructions apply to all tasks in this repository:

- Use Next.js with TypeScript for all website development.
- Keep components small and reusable.
- Use npm run dev for local development and npm run build to generate the site.
- The website is a simple business card for a carpenter in Radomsko.
- Provide pages: Home, About, Portfolio, Contact.
- Commit changes with clear messages in English.



# Agent Guidelines

These instructions apply to all tasks in this repository:

## General Project Info

This project is for a bespoke furniture-making company based in central Poland.  
The business offers made-to-measure furniture for apartments and houses, including kitchens, wardrobes, and built-in solutions tailored to individual customer needs.


## Development Stack

- Use **Next.js** with **TypeScript**
- Prefer reusable and modular components
- Keep the UI lightweight, elegant, and mobile-first
- No server-side logic – it's a purely static site
- Use free/open-source assets and fonts
- Avoid template footers or any third-party copyright

## Pages to Include

### 1. Home
- Hero section with company name, slogan, and CTA
- Showcase image or simple slider
- List of offered services (icons or short blurbs)
- Testimonials or trust section

### 2. About
- Short story about the company and its mission
- Image of the owner or workshop
- Section highlighting craftsmanship and quality

### 3. Contact
- Address (Radomsko region)
- Simple contact form able to send message to a passed gmailaddres
- Embedded Google Map
- Phone and email



## SEO & Performance

- Use semantic HTML
- Provide proper meta tags: title, description, open graph
- Compress images and use `next/image`
- Add alt text for accessibility
- Build static (`npm run build`) before deployment

## Git & Workflow

- Use clear, descriptive commit messages in **English**
- Use feature branches where necessary
- Run `npm run dev` locally for development
- Final deployable version should be fully static, exportable with `next export`

---

## 📌 Notes

- JSDoc-style comments must be written in **Polish**
- Site must be easy to extend in the future (e.g. portfolio, blog, pricing)
- Avoid unnecessary dependencies or visual clutter
