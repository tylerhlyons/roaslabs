# Next Level Dad Fitness — Lead Magnet Landing Page

A single-file landing page for the **"Shift-Proof Stretch Routine"** freebie.
Built to be sent from ManyChat (or any DM/email), get the prospect the free
value, then funnel the right people into a **free strategy call**.

On-brand with the Next Level Dad Fitness guide: dark/onyx background, Engine
Navy highlights, Tactical Gold accent, Bebas Neue headlines, Inter body.

---

## Do I need to pay to host it?

**No.** It's one static `index.html` — no server, no database. Host it free:

| Host | How | Cost |
|------|-----|------|
| **Netlify** (easiest) | Drag the folder onto [app.netlify.com/drop](https://app.netlify.com/drop) | Free |
| **Cloudflare Pages** | Connect this repo or upload the folder | Free |
| **GitHub Pages** | Repo → Settings → Pages → deploy from branch | Free |
| **Vercel** | Import the repo | Free |

You'll get a free URL like `nextleveldad.netlify.app`. Paste **that** into
ManyChat. Optional: point a custom domain at it later (~$10/yr for the domain
only — hosting stays free).

---

## What to customize before going live

Everything is in `index.html`. Search for these:

1. **Logo** — replace the inline `<svg class="logo-mark">` (top bar) with
   `<img src="logo.png" alt="Next Level Dad Fitness" class="logo-mark">` and
   drop your `logo.png` (the blue flame) in this folder. The SVG is just a
   placeholder so the page looks finished before you upload.

2. **Booking link** — find `https://YOUR-BOOKING-LINK.com` and swap in your
   Calendly / cal.com URL.
   - *Or* embed the full calendar: paste your scheduler's embed snippet inside
     the `<div class="booking-embed">` and delete the button above it.

3. **VSL / video** *(optional, when ready)* — the hero has a `#vsl` video slot
   with a play button. When you've got the video, replace the contents of
   `<div class="video-slot">` with your embed (YouTube/Vimeo/Wistia `<iframe>`).

4. **Stretch content** — the 9 moves are real, solid placeholders. Swap in your
   own stretches list / wording in the `<ol class="routine">` section any time.

5. **Social share image** *(optional)* — drop an `og-image.jpg` (1200×630) in
   this folder so the link shows a nice preview when shared.

---

## Notes

- Fully responsive (looks right on phones — most ManyChat traffic).
- A short medical disclaimer is in the footer (smart to keep for anything
  pain/stretch related).
- Want the booking CTA to appear only *after* the video plays ("timed reveal"),
  a countdown, or an opt-in email form? Easy add — just ask.
