# Canary Website - Oura Ring Inspired Design

A complete redesign of the Canary website using Oura Ring's UI/UX design patterns while maintaining all original Canary content and messaging.

## 🎨 Design Philosophy

This redesign combines:
- **Oura Ring's clean, modern aesthetic** - Professional navigation, rounded corners, elegant typography
- **Canary's powerful messaging** - Digital failsafe concept, security focus, journalist-friendly features
- **Interactive elements** - Step-by-step process, smooth animations, responsive design

## 📁 Project Structure

```
canary-oura-design/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── styles.css      # All styling (Oura-inspired design)
│   ├── js/
│   │   └── script.js       # Interactive functionality
│   └── images/
│       └── canary_bird.webp # Hero image
├── README.md               # This file
└── DESIGN_NOTES.md        # Design decisions and patterns
```

## 🚀 Features

### Design Elements (Inspired by Oura Ring)
- **Colored Navigation Tabs** - Each section has its own color theme
- **Clean Typography** - Inter font with italic emphasis for key phrases
- **Card-Based Layout** - Feature cards with colored borders
- **Rounded Corners** - Consistent 20px border radius throughout
- **Interactive Step Tabs** - Oura-style scenario navigation
- **Neutral Color Palette** - Cream/beige base with colorful accents

### Functionality
- **Smooth Scrolling Navigation** - Click nav items to scroll to sections
- **Interactive Step Process** - Click tabs to see different steps
- **Newsletter Signup** - Functional form with validation
- **Responsive Design** - Works on desktop, tablet, and mobile
- **Hover Effects** - Smooth animations and micro-interactions

### Content Sections
1. **Hero Section** - Main value proposition with canary bird image
2. **Origin Story** - Hackathon win and Cypherpunk Launchpad
3. **Core Features** - 4 key features with colored cards
4. **How It Works** - 5-step interactive process
5. **Newsletter** - Stay updated section
6. **Footer** - Links and branding

## 🛠 How to Use

### Option 1: Simple File Opening
1. Download/extract all files maintaining the folder structure
2. Open `index.html` in any modern web browser
3. All assets are locally referenced - no internet required

### Option 2: Local Server (Recommended)
1. Navigate to the project folder in terminal
2. Run a local server:
   ```bash
   # Python 3
   python3 -m http.server 8080
   
   # Python 2
   python -m SimpleHTTPServer 8080
   
   # Node.js (if you have it)
   npx serve .
   
   # PHP (if you have it)
   php -S localhost:8080
   ```
3. Open `http://localhost:8080` in your browser

### Option 3: Live Server (VS Code)
1. Install "Live Server" extension in VS Code
2. Right-click `index.html` and select "Open with Live Server"

## 🎯 Design Highlights

### Navigation
- **Color-coded tabs** like Oura Ring's navigation
- **Fixed header** with backdrop blur effect
- **Smooth scrolling** to sections

### Typography
- **Large headlines** with italic emphasis (inspired by Oura)
- **Section labels** in small caps
- **Clean hierarchy** with proper spacing

### Interactive Elements
- **Step tabs** that change content dynamically
- **Hover effects** on cards and buttons
- **Form validation** for newsletter signup
- **Smooth animations** throughout

### Color Scheme
- **Base**: Cream/beige backgrounds (#f8f7f4)
- **Primary**: Canary red (#e74c3c)
- **Accents**: Green, blue, orange, purple for different sections
- **Text**: Dark gray (#333) with lighter gray (#666) for descriptions

## 📱 Responsive Design

The website is fully responsive with breakpoints at:
- **Desktop**: 1200px+ (full layout)
- **Tablet**: 768px-1199px (adjusted grid)
- **Mobile**: <768px (stacked layout, mobile navigation)

## 🔧 Customization

### Colors
Edit the CSS custom properties in `styles.css`:
```css
:root {
  --primary-color: #e74c3c;
  --background-color: #f8f7f4;
  --text-color: #333;
}
```

### Content
All content is in `index.html` and can be easily modified:
- Headlines and descriptions
- Feature descriptions
- Step-by-step process
- Contact information

### Images
Replace `assets/images/canary_bird.webp` with your own hero image.
Recommended size: 400x400px or larger, optimized for web.

## 🌟 Key Improvements Over Original

1. **Professional Navigation** - Replaced tab-style with Oura's clean approach
2. **Better Visual Hierarchy** - Clear section divisions and typography
3. **Interactive Elements** - Step-by-step process with tabs
4. **Consistent Design System** - Unified colors, spacing, and components
5. **Enhanced Mobile Experience** - Fully responsive design
6. **Smooth Animations** - Hover effects and transitions
7. **Better Content Structure** - Scannable layout with visual breaks

## 📄 Browser Support

- **Chrome** 60+
- **Firefox** 60+
- **Safari** 12+
- **Edge** 79+

## 📞 Support

For questions about implementation or customization, refer to the code comments in each file. The design is built with standard HTML/CSS/JavaScript and should be easy to modify and extend.

---

**Built with inspiration from Oura Ring's exceptional UI/UX design patterns**

