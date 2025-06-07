# Kurdistan Modern News Portal

A modern, multi-language news website template featuring:
- Responsive design
- Live news updates
- Modern news cards and gallery
- Admin panel for adding news
- Language switcher (English, Kurdish, Arabic)
- Light/Dark mode toggle
- Quick poll and visitor counter
- Workshop/news section

## Files Included

- **index.htmlnews.html** — Main HTML file for the website
- **logo.webp** — Asayish Kurdistan logo (place in the same folder)
- **bragawra.jpg** — Example news image (place in the same folder)
- **README.md** — This documentation file

> If you use other images, make sure to download and place them in the same folder or update their URLs in the HTML.

## How to Run

1. Download or clone the repository.
2. Make sure all image files (like `logo.webp`, `bragawra.jpg`) are present in the project folder.
3. Open `index.htmlnews.html` in your browser.

## How to Publish

You can publish this website using any static hosting service, such as:

### GitHub Pages

1. Rename `index.htmlnews.html` to `index.html`.
2. Push your files to a GitHub repository.
3. Go to your repository settings → Pages → Set the source to your main branch.
4. Your site will be live at `https://yourusername.github.io/your-repo-name/`

### Netlify / Vercel / Surge

- Drag and drop your folder or connect your repository for instant deployment.

## Customization

- Edit the news data and content in `index.htmlnews.html`.
- To add a **Workshop** section, simply add a new news card or a dedicated section in the HTML file.  
  Example:
  ```html
  <div class="news-article">
      <img class="news-image" src="workshop-image.jpg" alt="Workshop">
      <div class="news-content-block">
          <div class="news-title">Upcoming Workshop: Digital Media Skills</div>
          <div class="news-meta">June 15, 2025 | Workshop</div>
          <div class="news-content">
              Join our hands-on workshop to learn the latest in digital media and journalism. Register now!
          </div>
          <a href="#" class="read-more">Read more &rarr;</a>
      </div>
  </div>
  ```
- Replace images as needed.
- Update styles in the `<style>` section for your branding.

---

**Designed by Naseh**