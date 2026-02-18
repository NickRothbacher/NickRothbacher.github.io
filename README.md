# NickRothbacher.github.io

Personal portfolio website for Nicolas Rothbacher — Senior Research Data Engineer at Apple (via TEKSystems). Previously Data Scientist at Stanford RegLab.

## Local Development

Open `index.html` directly in a browser. No build tools required.

## Adding a Profile Photo

To replace the initials avatar with a real photo:

1. Place your image at `assets/profile.jpg`
2. In `index.html`, replace:
   ```html
   <div class="avatar-initials">NR</div>
   ```
   with:
   ```html
   <img src="assets/profile.jpg" alt="Nicolas Rothbacher">
   ```

## Deployment

Push to the `master` (or `main`) branch — GitHub Pages will serve the site automatically at [nickrothbacher.github.io](https://nickrothbacher.github.io).
