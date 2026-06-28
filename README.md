# Naas Maths Grinds — Website

A single-page website for Naas Maths Grinds. Built with plain HTML/CSS/JS — no build step, no dependencies. Just open `index.html`.

## Preview it
Double-click `index.html` to open it in your browser. That's it.

## Brand
- **Navy** `#16294A` · **Grass green** `#2E7D32` · **Olive-gold** `#B8902F` · **Cream** `#FBF8F1`
- Fonts: Poppins (headings), Inter (body), Caveat (hand-written accents) — loaded from Google Fonts.
- Logo: `assets/logo.svg` (recreated to match your question-paper header).

## What to fill in  (search the page for `[` brackets)
Everything inside **square brackets `[ ]`** is a placeholder waiting for your info:

| Where | What to add |
|-------|-------------|
| Stats strip | students taught, years' experience, class size |
| Class cards | the **€ price** for each of the 3 classes |
| About section | your name, photo, and intro paragraphs |
| Testimonials | 3 real quotes from students/parents |
| FAQ | venue, times, pricing, class size answers |
| Contact | phone, email, address, class times, social links |

**Your photo:** drop a file into `assets/` and replace the grey "Add your photo" box in the About section with `<img src="assets/your-photo.jpg" alt="...">`.

## Make the contact form work (it's a dummy right now)
Easiest free option — **Formspree**:
1. Sign up at formspree.io, create a form, copy your form ID.
2. In `index.html` find `<form class="contact__form" action="#" ...>` and change it to:
   `<form class="contact__form" action="https://formspree.io/f/YOUR_ID" method="post">`
3. Delete the `onsubmit="return false"` and the grey ⚙️ note line.

Or skip the form entirely and just rely on the Call / WhatsApp / email buttons — they already work once you add your real number/email.

## Update phone & WhatsApp
Replace `353851234567` (used in `tel:` and `wa.me` links) with your real number — keep the `353` country code, drop the leading `0`.

## Putting it online (free)
Drag the whole folder into **Netlify Drop** (app.netlify.com/drop) or push to **GitHub Pages**. For a `.ie` / custom domain, point it at whichever host you choose.

## Files
```
index.html        the page
css/styles.css    all styling
js/main.js        menu, FAQ accordion, scroll animations
assets/logo.svg   logo
```
