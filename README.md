# USF Poker Club Website

A modern, responsive website for the University of South Florida Poker Club featuring the school's signature colors of green, white, and gold.

## 🃏 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Animated poker cards, hover effects, and smooth scrolling
- **Contact Form**: Functional membership signup form with validation
- **SEO Friendly**: Semantic HTML structure and proper meta tags
- **Fast Loading**: Optimized CSS and JavaScript for quick page loads

## 🎨 Design

- **Color Scheme**: USF Green (#006747), Gold (#ffcc00), and White
- **Typography**: Modern, readable fonts with proper hierarchy
- **Animations**: Subtle CSS animations and JavaScript interactions
- **Mobile-First**: Responsive design that works on all screen sizes

## 📁 File Structure

```
usf-poker-club/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Quick Start

### Local Development

1. **Clone or download** the files to your computer
2. **Open `index.html`** in your web browser
3. **That's it!** The website is fully functional locally

### File Setup

Make sure you have these three files in the same folder:

- `index.html` - The main webpage
- `styles.css` - All the styling
- `script.js` - Interactive functionality

## 🌐 Deployment on GitHub Pages

### Step 1: Create a GitHub Account

1. Go to [github.com](https://github.com) and sign up for a free account
2. Verify your email address

### Step 2: Create a New Repository

1. Click the **"+"** icon in the top right corner
2. Select **"New repository"**
3. Name your repository: `usf-poker-club-website` (or any name you prefer)
4. Make sure it's set to **"Public"**
5. Check **"Add a README file"**
6. Click **"Create repository"**

### Step 3: Upload Your Files

1. In your new repository, click **"uploading an existing file"**
2. Drag and drop or select these files:
   - `index.html`
   - `styles.css`
   - `script.js`
3. Write a commit message like: "Add USF Poker Club website files"
4. Click **"Commit changes"**

### Step 4: Enable GitHub Pages

1. In your repository, click **"Settings"** (top menu)
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select **"Deploy from a branch"**
4. Choose **"main"** branch and **"/ (root)"** folder
5. Click **"Save"**

### Step 5: Access Your Live Website

1. GitHub will show you a green checkmark and URL like:
   ```
   https://yourusername.github.io/usf-poker-club-website/
   ```
2. Your website is now live! 🎉
3. It may take a few minutes to become available

## 🔧 Customization

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
  --primary-green: #006747; /* Main green color */
  --light-green: #00a86b; /* Lighter green */
  --gold: #ffcc00; /* Gold/yellow color */
  --dark-gold: #cc9900; /* Darker gold */
}
```

### Updating Content

- **Club Information**: Edit the text in `index.html`
- **Events**: Update the events section with your actual dates and details
- **Contact Info**: Change email and social media links in the footer

### Adding Images

1. Upload images to your GitHub repository
2. Reference them in HTML like: `<img src="your-image.jpg" alt="description">`

## 📱 Sections Overview

### 🏠 Hero Section

- Eye-catching title and description
- Call-to-action buttons
- Animated poker cards

### ℹ️ About Section

- Club mission and values
- Feature highlights with icons
- Welcoming tone for new members

### 📅 Events Section

- Upcoming tournaments and workshops
- Date displays with event details
- Easy-to-scan format

### 🏆 Tournament Section

- Weekly tournament structure
- Special events information
- Clear formatting for rules

### 🤝 Join Section

- Membership benefits
- Contact form with validation
- Professional presentation

## 🛠️ Technical Details

### Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Grid and Flexbox
- **Vanilla JavaScript**: No external dependencies
- **Responsive Design**: Mobile-first approach

### Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

### Performance

- Optimized CSS and JavaScript
- Minimal external dependencies
- Fast loading times
- Smooth animations

## 📞 Support & Updates

### Making Changes

1. Edit files directly on GitHub:
   - Click on any file in your repository
   - Click the pencil icon to edit
   - Make your changes
   - Commit the changes
2. Changes will automatically update your live website

### Common Updates

- **New Events**: Edit the events section in `index.html`
- **Contact Info**: Update footer information
- **Colors**: Modify CSS custom properties
- **Text Content**: Change any text in the HTML file

## 🎯 SEO & Analytics

### Adding Google Analytics

Add this code before the closing `</head>` tag in `index.html`:

```html
<!-- Google Analytics -->
<script
  async
  src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"
></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag() {
    dataLayer.push(arguments);
  }
  gtag("js", new Date());
  gtag("config", "GA_TRACKING_ID");
</script>
```

### Improving SEO

- Update the `<title>` and `<meta description>` tags
- Add more specific keywords
- Include local SEO information for Tampa/USF area

## 🔗 Useful Links

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [HTML Reference](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)

## 📝 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

## 🎉 Congratulations!

You now have a professional website for your USF Poker Club! The site is:

- ✅ Mobile-friendly
- ✅ Fast loading
- ✅ Professional looking
- ✅ Easy to update
- ✅ Free to host

Good luck with your poker club! 🃏♠️♥️♦️♣️

---

**Need help?** Feel free to reach out or check the GitHub Issues section of your repository for troubleshooting.
