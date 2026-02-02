# Documentary-Movie-Review-Website

A modern, responsive website for documentary enthusiasts to write, share, and browse documentary movie reviews.

![Website Preview](https://images.unsplash.com/photo-1536440136628-849c177e76a1?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80)

## 🚀 Features

### **Core Features**
- ✍️ **Review Submission Form** - Submit reviews for any documentary movie
- ⭐ **Interactive Rating System** - 5-star rating with visual feedback
- 🎬 **Documentary Showcase** - Featured documentaries with details
- 📱 **Fully Responsive** - Works on all device sizes
- 🎨 **Modern UI/UX** - Clean, professional design with smooth animations

<img width="1887" height="3570" alt="image" src="https://github.com/user-attachments/assets/23fac0dc-89eb-4cdf-9074-3bfc2b072a8b" />

### **User Experience**
- Intuitive navigation and layout
- Hover effects and transitions
- Form validation and user feedback
- Recent reviews sidebar
- Website statistics dashboard

### **Documentary Categories**
- Nature & Environment
- History
- Science & Technology
- Social & Political
- Biography
- True Crime
- Arts & Culture

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript** - Form interactions and dynamic content
- **Font Awesome** - Icon library
- **Google Fonts** - Typography
- **Unsplash** - High-quality documentary images

## 📁 Project Structure

```
docureview/
│
├── index.html              # Main HTML file
│
├── FEATURES.md             # Detailed feature documentation
├── INSTALLATION.md         # Setup instructions
│
└── README.md               # This file
```

## 🚀 Quick Start

### Option 1: Direct Use
Simply open the `index.html` file in any modern web browser.

### Option 2: Live Server Development
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/docureview.git
   cd docureview
   ```

2. **Start a local server:**
   - Using Python:
     ```bash
     python -m http.server 8000
     ```
   - Using Node.js with `http-server`:
     ```bash
     npx http-server
     ```

3. **Open in browser:**
   Navigate to `http://localhost:8000`

## 📝 Usage Guide

### Writing a Review
1. Scroll to the "Write a Documentary Review" section
2. Fill in the documentary details:
   - Title (required)
   - Director
   - Release Year
   - Category
3. Rate the documentary using the star system
4. Write your review in the text area
5. Add your name (optional)
6. Click "Submit Review"

### Browsing Content
- **Featured Documentaries**: View curated documentary cards
- **Recent Reviews**: Check latest user submissions
- **Statistics**: See website engagement metrics

## 🎨 Customization

### Changing Colors
Modify the CSS variables in the `:root` selector:

```css
:root {
    --primary-color: #2c3e50;    /* Header & footer */
    --secondary-color: #3498db;  /* Buttons & accents */
    --accent-color: #e74c3c;     /* Highlights */
    --light-color: #ecf0f1;      /* Backgrounds */
}
```

### Adding New Documentaries
Edit the featured documentaries section in the HTML:

```html
<div class="doc-card">
    <div class="doc-img" style="background-image: url('YOUR_IMAGE_URL');"></div>
    <div class="doc-content">
        <h3 class="doc-title">Documentary Title</h3>
        <div class="doc-meta">
            <span>Year</span>
            <span class="doc-rating">[Stars]</span>
        </div>
        <p>Description here...</p>
    </div>
</div>
```

## 🔧 Form Customization

### Adding New Fields
To add additional fields to the review form:

1. Add HTML in the form section:
   ```html
   <div class="form-group">
       <label for="newField">Field Label</label>
       <input type="text" id="newField" placeholder="Placeholder">
   </div>
   ```

2. Update JavaScript validation if needed

### Modifying Categories
Edit the category select options in the form:
```html
<select id="category">
    <option value="">Select a category</option>
    <option value="new-category">New Category</option>
    <!-- Add more options here -->
</select>
```

## 🌐 Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Opera 50+

## 📱 Mobile Responsiveness

The website adapts to different screen sizes:

- **Desktop**: Full-width layout with sidebar
- **Tablet**: Single column layout
- **Mobile**: Optimized for small screens

## 🧪 Testing

### Manual Testing Checklist
- [ ] Form submission with valid data
- [ ] Form validation for required fields
- [ ] Star rating interaction
- [ ] Responsive design on different devices
- [ ] Navigation links
- [ ] Image loading
- [ ] Cross-browser compatibility

### Automated Testing
Add your preferred testing framework (Jest, Mocha, etc.) for:
- Form validation tests
- UI component tests
- Responsive design tests

## 🔄 Future Enhancements

### Planned Features
- [ ] User authentication system
- [ ] Database integration for persistent storage
- [ ] Search functionality
- [ ] Comment system on reviews
- [ ] User profiles
- [ ] Documentary recommendation engine
- [ ] Advanced filtering and sorting

### Technical Improvements
- [ ] Convert to React/Vue.js for better maintainability
- [ ] Implement REST API for reviews
- [ ] Add pagination for reviews
- [ ] Implement caching strategies
- [ ] Add Progressive Web App (PWA) capabilities

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contribution Guidelines
- Follow the existing code style
- Add comments for complex logic
- Update documentation as needed
- Test your changes thoroughly

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Images from [Unsplash](https://unsplash.com)
- Icons from [Font Awesome](https://fontawesome.com)
- Inspiration from various documentary platforms
- Contributors and testers

## 📞 Support

Om Gedam

GitHub: @itsomg134

Email: omgedam123098@gmail.com

Twitter (X): @omgedam

LinkedIn: Om Gedam

Portfolio: https://ogworks.lovable.app


## 📊 Analytics

To add analytics tracking, insert your tracking code before the closing `</body>` tag:

```html
<script>
    // Add your analytics code here
    // Example: Google Analytics
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());
    gtag('config', 'YOUR_GA_ID');
</script>
```

---

## 🎯 Quick Deployment

### GitHub Pages
1. Push to GitHub repository
2. Go to Settings > Pages
3. Select branch and folder
4. Your site will be live at: `https://yourusername.github.io/docureview`

### Netlify
1. Drag and drop the folder to Netlify
2. Or connect your GitHub repository
3. Automatic deployment on push

### Vercel
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

---

**Happy Documenting!** 🎬📝
