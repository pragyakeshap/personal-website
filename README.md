# Personal Website Portfolio

A clean, minimal, and responsive personal website built with HTML, CSS, and JavaScript.

## 🚀 Features

- **Fully Responsive** - Works perfectly on desktop, tablet, and mobile
- **Modern Design** - Clean and professional layout
- **Dark Mode Support** - Automatically adapts to system preferences
- **Smooth Animations** - Subtle fade-ins and hover effects
- **Fast Loading** - No heavy frameworks, just vanilla HTML/CSS/JS
- **SEO Friendly** - Semantic HTML structure

## 📋 Sections

1. **Hero/Home** - Introduction with profile image
2. **About** - Key characteristics and skills overview
3. **Skills** - Technologies and tools you've worked with
4. **Projects** - Showcase your portfolio projects
5. **Contact** - Links to your social profiles and email

## ✏️ Customization Guide

### 1. Update Personal Information

Edit `index.html`:

- **Line 7**: Update page title
- **Line 15**: Change initials in navigation (YN → Your Initials)
- **Line 32**: Update profile image URL
- **Line 35**: Change your name
- **Line 36**: Update job title/subtitle
- **Lines 37-41**: Write your bio/introduction
- **Lines 195-210**: Update contact links and email

### 2. Customize Colors

Edit `styles.css` (lines 2-11):

```css
:root {
    --primary-color: #3b82f6; /* Your brand color */
    --secondary-color: #1e40af; /* Darker shade */
    /* ... */
}
```

### 3. Add Your Projects

Edit the project cards in `index.html` (starting around line 125):

- Replace placeholder images
- Update project titles and descriptions
- Add your tech stack tags
- Link to live demos and GitHub repos

### 4. Update Skills

Edit the skills section in `index.html` (around line 110) - add or remove skill tags as needed.

### 5. Modify About Section

Edit the characteristic cards in `index.html` (around line 50) to reflect your unique qualities.

## 🌐 Deployment Options (All FREE!)

### Option 1: Netlify (Recommended - Easiest)

1. Create account at [netlify.com](https://netlify.com)
2. Drag and drop your folder to Netlify
3. Done! You get a free subdomain (e.g., yourname.netlify.app)
4. Optional: Connect custom domain for ~$10-15/year

**Steps:**
```bash
# Install Netlify CLI (optional)
npm install -g netlify-cli

# Deploy
netlify deploy --prod
```

### Option 2: GitHub Pages

1. Create a GitHub repository named `yourusername.github.io`
2. Push your code:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```
3. Enable GitHub Pages in repo settings
4. Your site will be at `https://yourusername.github.io`

### Option 3: Vercel

1. Create account at [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Deploy with one click
4. Free subdomain provided

### Option 4: Cloudflare Pages

1. Create account at [pages.cloudflare.com](https://pages.cloudflare.com)
2. Connect your GitHub repo
3. Deploy automatically
4. Free CDN and SSL included

## 💰 Cost Breakdown

- **Hosting**: $0 (using any option above)
- **Domain** (optional): ~$10-15/year
- **SSL Certificate**: $0 (included with all platforms)

**Total: $0-15/year**

## 🛠️ Local Development

Simply open `index.html` in your browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## 📱 Testing Responsiveness

- Chrome DevTools (F12 → Toggle Device Toolbar)
- Test on actual devices
- Use [responsively.app](https://responsively.app)

## 🎨 Design Inspirations

- Minimalist portfolio design
- Clean typography
- Modern card-based layouts
- Subtle animations

## 📝 Adding a Blog (Optional)

To add a blog section:

1. Create a `blog/` folder
2. Add individual HTML pages for each post
3. Create a blog index page listing all posts
4. Update navigation to include blog link

## 🔧 Advanced Enhancements

- Add a contact form using [Formspree](https://formspree.io) (free tier available)
- Integrate Google Analytics
- Add a resume/CV download button
- Include a testimonials section
- Add project filtering by technology

## 📄 License

Feel free to use this template for your personal website!

## 🤝 Need Help?

- Check the code comments in each file
- All styling is in `styles.css` with clear section labels
- JavaScript functionality is in `script.js` with explanations

---

**Built with ❤️ using vanilla HTML, CSS & JavaScript**
