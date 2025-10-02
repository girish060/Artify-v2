# Artify - Digital Art Marketplace Platform

A modern, fully-functional multi-page web application for digital art marketplace built with HTML5, CSS3 (TailwindCSS), and Vanilla JavaScript.

## 🎨 Project Overview

Artify is a comprehensive digital art platform that allows users to discover, purchase, and upload artwork. The platform features a complete e-commerce experience with user authentication, shopping cart functionality, payment processing, and a creator dashboard.

## 📁 Project Structure

```
Artify/
├── index.html          # Main homepage with featured artworks
├── artworks.html       # Complete artwork gallery with filtering
├── login.html          # User authentication (login/signup)
├── payment.html        # Secure checkout and payment processing
├── creator.html        # Artist dashboard for uploading artwork
├── trending.html       # Trending and popular artworks
├── Attraction.html     # Gallery showcase page
├── user.html           # User profile and account management
├── join.html           # Additional signup page
├── README.md           # Project documentation
└── DEPLOYMENT.md       # Deployment instructions
```

## ✨ Features

### Core Functionality
- **Multi-page Architecture**: Organized into distinct functional pages
- **Responsive Design**: Mobile-first approach, works on all devices
- **Modern UI/UX**: Beautiful gradients, animations, and interactive elements
- **Demo Content**: Sample artworks with clear demo labeling

### User Features
- **User Authentication**: Complete signup/login system with form validation
- **Shopping Cart**: 
  - Add/remove items with persistent storage
  - Real-time cart count updates
  - Beautiful cart modal interface
  - Checkout integration
- **Artwork Discovery**:
  - Search and filter functionality
  - Category-based browsing
  - Sorting options (price, popularity, newest)
- **Wishlist**: Save favorite artworks for later
- **Payment Processing**: Secure checkout with multiple payment options

### Creator Features
- **Artwork Upload**: Drag-and-drop file upload with preview
- **Portfolio Management**: Organize and showcase artwork
- **Sales Tracking**: Monitor artwork performance

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional but recommended)

### Installation & Setup

1. **Clone or Download**
   ```bash
   git clone <your-repo-url>
   cd Artify
   ```

2. **Run Local Server** (Recommended)
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Open in Browser**
   - With server: `http://localhost:8000`
   - Direct file: Open `index.html` in your browser

## 🛠️ Technology Stack

### Frontend
- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Custom styles with TailwindCSS framework
- **JavaScript (ES6+)**: Modern vanilla JavaScript for all functionality

### External Libraries (CDN)
- **TailwindCSS**: Utility-first CSS framework
- **Font Awesome**: Comprehensive icon library
- **AOS (Animate On Scroll)**: Scroll-triggered animations
- **Google Fonts**: Inter font family for modern typography

### Browser Storage
- **LocalStorage**: User sessions, cart persistence, wishlist data

## 🎯 Key Pages & Functionality

### 1. Homepage (`index.html`)
- Hero section with call-to-action
- Featured artworks with demo content
- Platform statistics and features
- Newsletter subscription
- Complete navigation system

### 2. Artworks Gallery (`artworks.html`)
- Dynamic artwork grid with 14+ demo pieces
- Advanced filtering by category
- Sorting options (price, popularity, date)
- Search functionality
- Add to cart and wishlist features

### 3. User Authentication (`login.html`)
- Dual-mode login/signup forms
- Client-side form validation
- Password visibility toggle
- Social login buttons (UI ready)
- Session management

### 4. Payment System (`payment.html`)
- Multi-step checkout process
- Dynamic price calculations (subtotal, fees, taxes)
- Multiple payment methods (Credit Card, UPI, PayPal)
- Order summary with item details
- Discount code functionality

### 5. Creator Dashboard (`creator.html`)
- Artwork upload with drag-and-drop
- Image preview functionality
- Metadata input (title, price, description, category)
- Portfolio management

### 6. Trending Page (`trending.html`)
- Popular artwork showcase
- Trending indicators
- Featured artist highlights

## 🛒 Shopping Cart System

The cart system works across all pages with:
- **Persistent Storage**: Items saved in browser localStorage
- **Real-time Updates**: Cart count updates instantly
- **Modal Interface**: Beautiful popup with item management
- **Cross-page Sync**: Cart state maintained across navigation
- **Checkout Integration**: Seamless flow to payment page

## 🎨 Demo Content

The platform includes professionally curated demo content:
- **14+ Sample Artworks**: Various categories and price points
- **Demo Labels**: Clear orange badges indicating demo content
- **Realistic Data**: Proper pricing, ratings, and sales numbers
- **Artist Attribution**: Consistent "Demo Artist" branding

## 📱 Responsive Design

- **Mobile-first**: Optimized for mobile devices
- **Tablet Support**: Perfect iPad and tablet experience
- **Desktop Enhanced**: Full-featured desktop interface
- **Touch Friendly**: Optimized for touch interactions

## 🎨 Customization

### Styling
- Modify TailwindCSS classes for quick design changes
- Custom CSS variables for brand colors
- Gradient and animation utilities

### Content
- Update demo artwork data in JavaScript arrays
- Modify text content and copy
- Replace placeholder images with actual artwork

### Features
- Add new payment methods
- Integrate real backend APIs
- Extend user profile functionality

## 🚀 Deployment Options

See `DEPLOYMENT.md` for detailed deployment instructions including:
- GitHub Pages (recommended)
- Netlify
- Vercel
- Firebase Hosting

## 📊 Performance Features

- **Optimized Images**: Properly sized and compressed demo images
- **CDN Resources**: Fast loading external libraries
- **Minimal JavaScript**: Efficient vanilla JS implementation
- **CSS Optimization**: TailwindCSS utility classes
- **Local Storage**: Efficient client-side data management

## 🔧 Browser Compatibility

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Development Notes

### Code Organization
- Each HTML file is self-contained with embedded CSS and JavaScript
- Consistent navigation across all pages
- Modular JavaScript functions for reusability
- Clean, commented code for maintainability

### Best Practices
- Semantic HTML structure
- Accessible design patterns
- Progressive enhancement
- Mobile-first responsive design
- Performance optimization

## 🤝 Contributing

This project is set up for easy customization and extension:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test across different pages
5. Submit a pull request

## 📄 License

This project is open source and available under the MIT License.

## 🎯 Future Enhancements

Potential improvements for the platform:
- Backend integration for real user accounts
- Payment gateway integration
- Advanced search with filters
- Artist verification system
- NFT marketplace features
- Mobile app development

---

**Built with ❤️ for the creative community**

*Artify - Where Creativity Lives & Thrives*
