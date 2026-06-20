# Hit Radio Live Website

Your 4-page website, ready to customize and deploy.

## Files

- `index.html` — Home page
- `songlist.html` — Song list (~100 songs)
- `gallery.html` — Photo gallery (20 placeholders)
- `book.html` — Book Us / contact form
- `styles.css` — Shared styling for all pages

## How to preview on your iPhone

1. Save all files to a folder called `hitradiolive`
2. Open the Files app
3. Tap `index.html` — it'll open in Safari and show your site

## What you need to swap in later

### 1. Band photo on home page
Find this in `index.html`:
```
<div class="hero-image placeholder">BAND PHOTO GOES HERE</div>
```
Replace with:
```
<img src="band-photo.jpg" alt="Hit Radio Live" class="hero-image">
```

### 2. YouTube video on home page
Find this in `index.html`:
```
<div class="video-placeholder">...</div>
```
Replace with (using your actual YouTube video ID):
```
<iframe width="100%" height="100%" src="https://www.youtube.com/embed/YOUR_VIDEO_ID" frameborder="0" allowfullscreen></iframe>
```

### 3. Gallery photos
In `gallery.html`, each gallery item looks like:
```
<div class="gallery-item"><div class="placeholder">PHOTO 1</div></div>
```
Replace with:
```
<div class="gallery-item"><img src="photo1.jpg" alt=""></div>
```

### 4. Logo (optional)
In the nav bar of each page, you'll see `HIT RADIO LIVE` as text. To use an image logo, replace:
```
<a href="index.html" class="nav-logo">HIT RADIO LIVE</a>
```
With:
```
<a href="index.html" class="nav-logo"><img src="logo.png" alt="Hit Radio Live" style="height: 48px;"></a>
```

## Deploying to your domain

Easiest free options:
- **Netlify Drop** (netlify.com/drop) — just drag folder, get URL
- **GitHub Pages** — free, slightly more technical
- **Cloudflare Pages** — free, great performance

Once deployed, point `hitradiolive.net` to the new host via DNS settings.
