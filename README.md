# AWWA Family Management System

A modern, responsive web application for managing military families and personnel information, specifically designed for the **624 EME BN (Battalion)**. The system is called "दीप" (Deep) with the tagline "जागरूकता से आत्मनिर्भरता" (Awareness to Self-reliance).

> **⚠️ Note**: The mobile navigation toggle functionality needs to be fixed by **Jyoti**. The current implementation has issues with the toggle button visibility and functionality on mobile devices.

## 🚀 Features

### **Modern Web Architecture**
- **HTML5** with semantic markup
- **CSS3** with modern features and animations
- **Vanilla JavaScript** for interactivity
- **Chart.js** for interactive data visualization
- **Font Awesome** for icons
- **Custom CSS Grid** and Flexbox layouts

### **Enhanced UI/UX**
- **Responsive Design** - Works on all devices (desktop, tablet, mobile)
- **Modern UI Components** - Clean, professional interface
- **Smooth Animations** - CSS transitions and transforms
- **Interactive Charts** - 6 different chart types with hover effects
- **Mobile-First Design** - Optimized for mobile devices
- **Accessibility** - Keyboard navigation and screen reader support

### **Dashboard Features**
- **Static Statistics** - Family and children counts
- **Interactive Analytics** - 6 different chart visualizations
- **User Management** - Role-based access control
- **Google Sheets Integration** - Families section (needs fixing by Jyoti and Adab)
- **Responsive Sidebar** - Mobile navigation (needs fixing by Jyoti)
- **Modern Header** - User profile and logout functionality

## 🛠️ Technology Stack

### **Frontend**
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with Grid and Flexbox
- **Vanilla JavaScript** - Client-side interactivity
- **Chart.js** - Data visualization library
- **Font Awesome** - Icon library

### **Styling**
- **Custom CSS** - Tailored styling and animations
- **CSS Grid** - Modern layout system
- **Flexbox** - Flexible component layouts
- **Media Queries** - Responsive design
- **CSS Variables** - Consistent theming

### **Development**
- **Static HTML** - No build process required
- **Browser DevTools** - Development and debugging
- **Git** - Version control

## 📦 Installation

### **Prerequisites**
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### **Setup Instructions**

1. **Clone Repository**
   ```bash
   git clone [repository-url]
   cd Awwa_prototype
   ```

2. **Open in Browser**
   - Simply open `login.html` in your web browser
   - Or use a local server for development

3. **For Development Server** (optional)
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

## 🎯 Project Structure

```
Awwa_prototype/
├── login.html                   # Main authentication portal
├── dashboard_super user.html    # Main dashboard with all features
├── styles.css                   # Login page styling
├── dashboard.css                # Dashboard styling
├── public/                      # Assets and images
│   ├── Ams Vedant.ttf          # Custom Hindi font
│   ├── Awwa2-logo.png          # Main logo
│   ├── Col.jpg                 # Background image
│   ├── profile.png             # Default profile image
│   ├── harish.jpeg             # User profile images
│   ├── piyush.jpeg             # User profile images
│   ├── Rahul.jpeg              # User profile images
│   └── [other assets]          # Essential images and resources
└── README.md                   # This file
```

## 🔐 Authentication

### **User Roles**
- **Admin** - Full system access
- **L1** - Super user access
- **L2** - Standard user access
- **L3** - Limited user access
- **L4** - Basic user access

### **Test Credentials**
- **Admin**: `tarunpreet singh` / `admin123` / `admin`
- **Admin**: `piyush sharma` / `admin123` / `admin`
- **Admin**: `harish kumar` / `admin123` / `admin`
- **Admin**: `rahul t more` / `admin123` / `admin`
- **Admin**: `admin` / `admin123` / `admin`
- **Admin**: `bt01` / `admin123` / `admin`
- **L1**: `aditi` / `admin123` / `L1`
- **L1**: `user1` / `admin123` / `L1`
- **L1**: `test` / `admin123` / `L1`
- **L2**: `user2` / `admin123` / `L2`
- **L3**: `user3` / `admin123` / `L3`
- **L4**: `user4` / `admin123` / `L4`

## 📊 Dashboard Features

### **Statistics Cards**
- Total Families: 274
- Total Children: 509
- Registered Families: 274
- IVF Cases: 2
- Special Children: 1
- Marital Discord: 2

### **Interactive Charts**
1. **Family Medical Status** - Doughnut chart
2. **Parental Education Level** - Horizontal bar chart
3. **Workshop Distribution** - Vertical bar chart
4. **Children Gender Distribution** - Pie chart
5. **Children Age Profile** - Radar chart
6. **Family Size Distribution** - Polar area chart

## 🎨 UI/UX Improvements

### **Modern Design**
- **Clean Interface** - Minimalist, professional design
- **Consistent Colors** - Cohesive color scheme
- **Typography** - Custom Hindi font (Ams Vedant) and modern fonts
- **Spacing** - Consistent spacing and layout

### **Animations**
- **CSS Transitions** - Smooth hover effects
- **Chart Animations** - Smooth chart rendering
- **Interactive Elements** - Visual feedback on interactions
- **Mobile Transitions** - Smooth mobile navigation

### **Responsive Design**
- **Mobile First** - Optimized for mobile devices
- **Tablet Support** - Perfect tablet experience
- **Desktop Enhanced** - Full desktop features
- **Touch Friendly** - Mobile-optimized interactions
- **⚠️ Mobile Navigation** - Toggle functionality needs fixing by Jyoti

## 🚀 Performance

### **Optimizations**
- **Static HTML** - Fast loading with no build process
- **Optimized CSS** - Efficient styling and animations
- **Minimal JavaScript** - Lightweight interactivity
- **Compressed Assets** - Optimized images and fonts

### **Loading Times**
- **Instant Load** - No build process required
- **Smooth Transitions** - CSS-based animations
- **Efficient Charts** - Optimized chart rendering
- **Mobile Optimized** - Fast mobile performance

## 🔧 Development

### **File Structure**
- **HTML Files** - Main application pages
- **CSS Files** - Styling and responsive design
- **JavaScript** - Client-side functionality
- **Assets** - Images, fonts, and resources

### **Code Quality**
- **Clean HTML** - Semantic markup
- **Organized CSS** - Modular styling approach
- **Commented Code** - Well-documented functionality
- **Error Handling** - Basic error management

## 🌟 Key Benefits

### **Developer Experience**
- **Simple Setup** - No build process required
- **Easy Debugging** - Browser developer tools
- **Fast Development** - Direct HTML/CSS/JS editing
- **Version Control** - Git-friendly development

### **User Experience**
- **Intuitive Navigation** - Easy-to-use interface
- **Fast Performance** - Optimized for speed
- **Accessibility** - Keyboard navigation support
- **Mobile Responsive** - Works on all devices
- **⚠️ Mobile Navigation** - Toggle needs fixing by Jyoti

### **Maintainability**
- **Clean Code** - Well-organized, documented code
- **Modular Structure** - Easy to extend and modify
- **Static Files** - Simple deployment
- **Cross-Platform** - Works on any web server

## 📱 Browser Support

- **Chrome** (recommended)
- **Firefox**
- **Safari**
- **Edge**
- **Mobile browsers** (iOS Safari, Chrome Mobile)

## 🎯 Next Steps

1. **Open Project**: Open `login.html` in your browser
2. **Login**: Use any test credentials from the list above
3. **Explore**: Navigate through the dashboard
4. **Mobile Testing**: Test on mobile devices (navigation needs fixing by Jyoti)
5. **Development**: Edit HTML/CSS/JS files directly

## 🐛 Known Issues

### **Critical Issues (Needs Immediate Attention)**
- **Mobile Navigation Toggle**: The toggle button functionality needs to be fixed by **Jyoti**
- **Header Layout**: The header positioning (title to extreme left, logout to extreme right) needs to be fixed by **Jyoti**
  - **CSS Issues**: Current flexbox implementation not working properly
  - **Layout Problems**: Title and logout button positioning not as expected
- **Google Sheets Integration**: The families section Google Sheets integration needs to be fixed by **Jyoti and Adab**
  - **CORS Proxy Reliability**: Multiple proxy fallbacks may fail intermittently
  - **Data Mapping Issues**: Column name mapping inconsistencies causing "N/A" values
  - **CSV Parsing Problems**: Some data fields not being parsed correctly
  - **Error Handling**: Better error messages and fallback mechanisms needed

### **Minor Issues**
- **Chart Responsiveness**: Some charts may need mobile optimization
- **Cross-browser Testing**: Needs testing across different browsers

## 📄 License

This project is developed for the 624 EME BN and is proprietary software.

---

**Built with ❤️ using HTML5, CSS3, JavaScript, and Chart.js**
