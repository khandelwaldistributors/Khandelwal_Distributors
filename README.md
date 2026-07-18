# Khandelwal Distributors — Website

## What's inside
- `index.html` — Home
- `about.html` — About Us
- `services.html` — Services & Products
- `why-us.html` — Why Choose Us (credentials, DL/GST numbers)
- `contact.html` — Contact (address, map, enquiry form, WhatsApp)
- `css/style.css` — all styling
- `assets/` — logo files + nav script
- `sitemap.xml`, `robots.txt` — for SEO/search engines

## Before going live — 3 things to fix

1. **Domain placeholder**: every page currently has `https://www.yourdomain.com` in
   the `<link rel="canonical">`, Open Graph tags, and JSON-LD schema (in
   `index.html`), plus in `sitemap.xml` and `robots.txt`. Once you buy your real
   domain, find-and-replace `yourdomain.com` with your actual domain across all
   these files.

2. **Contact form**: the enquiry form on `contact.html` points to
   `https://formspree.io/f/YOUR_FORM_ID`. Static sites can't process form
   submissions on their own, so:
   - Go to https://formspree.io, sign up free (50 submissions/month free tier)
   - Create a form, copy your form ID
   - Replace `YOUR_FORM_ID` in `contact.html` with it
   Submissions will then land in your email inbox automatically.

3. **Stock images** (optional): the site currently uses no photos, just clean
   cards and icons — matches the "no real photos" decision. If you'd like a
   hero image or section photos added later, just ask and I'll source and
   integrate quality stock images.

## How to host this for free (GitHub Pages)

1. Create a free GitHub account at github.com if you don't have one
2. Create a new repository (e.g., `khandelwal-website`)
3. Upload all files in this folder to that repository (drag-and-drop works
   on github.com, or use git)
4. Go to repository Settings → Pages → set source to the `main` branch, root
   folder → Save
5. Your site will be live at `https://yourusername.github.io/khandelwal-website/`
   within a couple of minutes
6. Once you buy your domain, go to Settings → Pages → add your custom domain,
   then set up DNS records at your domain registrar (Hostinger/BigRock) as
   GitHub instructs — this points your domain to the free GitHub Pages hosting
