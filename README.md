# Akka Nasi Lemak JB — Static Site

A mobile-first static website for Akka Nasi Lemak JB, ready for GitHub Pages.

## Setup

1. Add your images to `assets/`:
   - `logo.png` (hawker-style, kertas bungkus motif)
   - `hero.jpg` (banana leaf on kertas bungkus hero shot)
   - `gallery-1.jpg`, `gallery-2.jpg`, `gallery-3.jpg`
   - `favicon.ico`

2. Update content in `index.html`:
   - Replace the Location text and Google Maps embed with the real stall address.
   - Adjust any copy to match your brand tone.

3. Commit and push:
   ```bash
   git init
   git add .
   git commit -m "Akka Nasi Lemak JB site v1"
   git branch -M main
   git remote add origin https://github.com/USERNAME/akka-nasi-lemak-jb.git
   git push -u origin main
