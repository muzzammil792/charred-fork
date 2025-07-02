# Sakura Garden - Japanese Fusion Restaurant Website

A modern, elegant restaurant website for Sakura Garden, a Japanese fusion dining establishment. This website features a unique design inspired by cherry blossoms and zen aesthetics, with smooth animations and interactive elements.

## 🌸 Features

### Design & Aesthetics
- **Japanese-inspired design** with cherry blossom animations
- **Modern gradient backgrounds** and elegant typography
- **Responsive layout** that works on all devices
- **Smooth scroll animations** and parallax effects
- **Interactive hover effects** and micro-animations

### Sections
1. **Hero Section** - Stunning landing with animated cherry blossoms
2. **About Section** - Restaurant story and philosophy
3. **Menu Section** - Interactive menu with categories
4. **Experience Section** - Dining atmosphere and services
5. **Gallery Section** - Beautiful food and restaurant photos
6. **Contact Section** - Reservation form and contact information
7. **Footer** - Additional links and newsletter signup

### Interactive Features
- **Mobile-responsive navigation** with hamburger menu
- **Tabbed menu system** with smooth transitions
- **Reservation form** with validation
- **Newsletter subscription**
- **Smooth scrolling** navigation
- **Parallax effects** on floating elements
- **Counter animations** for statistics
- **Image lazy loading** for performance
- **Notification system** for form submissions

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (ES6+)** - Interactive functionality
- **Font Awesome** - Icons
- **Google Fonts** - Typography (Cormorant Garamond, Inter)
- **Unsplash** - High-quality images

## 🎨 Design Elements

### Color Palette
- **Primary Red**: #e74c3c (Cherry blossom inspired)
- **Dark Red**: #c0392b
- **Dark Blue**: #2c3e50
- **Light Gray**: #f8f9fa
- **Text Gray**: #7f8c8d

### Typography
- **Headings**: Cormorant Garamond (elegant serif)
- **Body Text**: Inter (clean sans-serif)

### Animations
- Cherry blossom falling animation
- Floating element parallax effects
- Smooth section reveal animations
- Button hover effects with ripple
- Menu item hover transformations

## 📱 Responsive Design

The website is fully responsive and optimized for:
- **Desktop** (1200px+)
- **Tablet** (768px - 1199px)
- **Mobile** (320px - 767px)

## 🚀 Getting Started

1. **Clone or download** the project files
2. **Open `index.html`** in your web browser
3. **No build process required** - it's ready to use!

### File Structure
```
Sakura Garden/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎯 Key Features Explained

### Cherry Blossom Animation
The hero section features animated cherry blossoms that fall continuously, creating a serene Japanese atmosphere.

### Interactive Menu
The menu section uses JavaScript to create smooth transitions between different food categories (Starters, Main Courses, Sushi & Sashimi, Desserts).

### Reservation System
A fully functional reservation form with:
- Real-time validation
- Date and time selection
- Guest count options
- Success/error notifications

### Performance Optimizations
- **Lazy loading** for gallery images
- **Preloading** of critical images
- **Smooth animations** using CSS transforms
- **Efficient event handling**

## 🎨 Customization

### Changing Colors
Modify the CSS custom properties in `styles.css`:
```css
:root {
    --primary-color: #e74c3c;
    --secondary-color: #c0392b;
    --text-color: #2c3e50;
}
```

### Adding Menu Items
Add new menu items in the HTML structure:
```html
<div class="menu-item">
    <div class="menu-item-image">
        <img src="path-to-image.jpg" alt="Dish Name">
    </div>
    <div class="menu-item-content">
        <div class="menu-item-header">
            <h3>Dish Name</h3>
            <span class="price">$XX</span>
        </div>
        <p>Description of the dish</p>
        <div class="menu-item-tags">
            <span class="tag">Vegan</span>
        </div>
    </div>
</div>
```

### Modifying Animations
Adjust animation timing and effects in the CSS:
```css
@keyframes fall {
    0% { transform: translateY(-100px) rotate(0deg); opacity: 0; }
    100% { transform: translateY(100vh) rotate(360deg); opacity: 0; }
}
```

## 🌟 Browser Support

- **Chrome** 60+
- **Firefox** 55+
- **Safari** 12+
- **Edge** 79+

## 📞 Contact Information

For questions about this website template:
- **Restaurant Name**: Sakura Garden
- **Location**: 123 Zen Street, Downtown District
- **Phone**: (555) 123-4567
- **Email**: info@sakuragarden.com

## 📄 License

This project is created for demonstration purposes. Feel free to use and modify for your own restaurant website.

## 🙏 Acknowledgments

- **Unsplash** for high-quality restaurant and food photography
- **Font Awesome** for beautiful icons
- **Google Fonts** for elegant typography
- **Modern CSS techniques** for smooth animations

---

*Experience the perfect harmony of Japanese tradition and modern culinary innovation at Sakura Garden.* 🌸 