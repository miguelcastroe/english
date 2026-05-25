# Miguel Castro — Portfolio

Personal portfolio of Miguel Castro, Creative Director based in Lima - available worldwide.

---

## About

Single-page portfolio built in plain HTML and CSS. No frameworks, no build tools, no dependencies. The design follows Dieter Rams' principle of as little as possible: Inter typeface, black and white, functional structure.

---

## Structure

```
index.html          Main page
hero_boy.png        Hero portrait
action_boy.png      About section photo
og.png              Open Graph image (1200×630)
favicon.ico         Favicon
favicon.png         Favicon (32×32 PNG)
README.md           This file
```

---

## Sections

- **Hero** — Name, photo, capabilities
- **Work** — Six selected cases with inline Vimeo video, unseen layer, role, awards
- **Pull quote** — Between work and about
- **About** — Photo, bio, AI approach
- **Experience** — Draggable carousel of nine agencies
- **Footer** — Copyright

---

## Deployment

The site is a single HTML file with local image assets. No build step required.

**GitHub Pages:**
1. Push this repository to GitHub
2. Go to Settings → Pages
3. Set source to `main` branch, root folder
4. The site will be live at `https://yourusername.github.io/repository-name`

**Custom domain (miguelcastro.cc):**
1. Add a `CNAME` file to the repository root containing `miguelcastro.cc`
2. In your DNS provider, add an A record pointing to GitHub Pages IPs:
   ```
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```
3. Or add a CNAME record pointing `www` to `yourusername.github.io`
4. Enable HTTPS in Settings → Pages once DNS propagates

---

## Updating content

**To replace photos:** swap `hero_boy.png` or `action_boy.png` with new files of the same name, or update the `src` attributes in the HTML.

**To update the OG image:** replace `og.png` with a new 1200×630px image.

**To update copy or awards:** edit the relevant sections directly in `miguel-castro.html`. The structure is clearly commented.

**To add a Vimeo video:** the six `<iframe>` src attributes each contain a Vimeo video ID. Replace the ID number to swap a video.

---

## Design notes

- Typography: Inter 400 and 500 only
- Sizes: 11px labels, 13px body, 15px case titles, 20px section labels, variable hero name
- Colors: `#111111` primary, `#888888` secondary, `#e8e8e8` lines, `#e8a020` Grand Prix accent only
- All lines run full viewport width
- Photos render in grayscale via CSS filter
- No JavaScript frameworks. Vanilla JS for the hamburger nav and experience carousel only.

---

## Contact

miguel@miguelcastro.cc
[linkedin.com/in/miguelcastroe](https://www.linkedin.com/in/miguelcastroe/)
