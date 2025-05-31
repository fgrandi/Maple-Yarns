# My GitHub Pages Site

A modern, responsive website built with HTML, CSS, and JavaScript, designed to be hosted on GitHub Pages.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Fast Loading**: Optimized for performance with minimal dependencies
- **SEO Friendly**: Structured for search engine optimization
- **Easy to Customize**: Well-organized code that's easy to modify

## 🛠️ Technologies Used

- HTML5 with semantic markup
- CSS3 with modern features (Grid, Flexbox, CSS Variables)
- Vanilla JavaScript (ES6+)
- Google Fonts (Inter)
- GitHub Pages for hosting

## 📁 Project Structure

```
.
├── index.html              # Main HTML file
├── styles/
│   └── main.css           # All CSS styles
├── scripts/
│   └── main.js            # JavaScript functionality
├── _config.yml            # GitHub Pages configuration
├── .github/
│   ├── workflows/
│   │   └── pages.yml      # GitHub Actions for deployment
│   └── copilot-instructions.md
└── README.md              # This file
```

## 🚀 Getting Started

### Local Development

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. Open `index.html` in your browser to view the site locally, or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

3. Open `http://localhost:8000` in your browser

### Deploy to GitHub Pages

1. Push your code to a GitHub repository
2. Go to your repository settings
3. Navigate to "Pages" in the sidebar
4. Select "Deploy from a branch" as the source
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

Your site will be available at `https://yourusername.github.io/repository-name`

## ✏️ Customization

### Content
- Edit `index.html` to update the content
- Modify the sections to match your needs
- Update contact links with your actual social media profiles

### Styling
- All styles are in `styles/main.css`
- CSS variables at the top of the file control colors and spacing
- The design uses a mobile-first responsive approach

### Functionality
- JavaScript is in `scripts/main.js`
- Includes smooth scrolling, mobile menu, and scroll animations
- Add your own interactive features as needed

### Configuration
- Update `_config.yml` with your site information
- Modify the GitHub Actions workflow if needed (`.github/workflows/pages.yml`)

## 📱 Responsive Breakpoints

- Mobile: < 768px
- Tablet: 768px - 1024px  
- Desktop: > 1024px

## 🎨 Color Scheme

The site uses CSS variables for easy color customization:

- Primary: #6366f1 (Indigo)
- Secondary: #64748b (Slate)
- Accent: #06b6d4 (Cyan)
- Text: #1e293b (Dark Slate)

## 🔧 Browser Support

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Support

If you have any questions or need help, please open an issue in this repository.

---

**Built with ❤️ for the web**
