# Groceries4U - Online Grocery Store

A modern, responsive e-commerce website for online grocery shopping built with HTML, CSS, and JavaScript.

## Features

- **User Authentication**: Login and registration system with smooth transitions
- **Product Categories**: Multiple categories including:
  - General items (Coffee, Tea, Sugar, Spices)
  - Fresh Fruits
  - Rice varieties
  - Cooking Oils
  - Masalas (Spice blends)
  - Nuts
  - Spices
  - Flours
- **Shopping Cart**: Dynamic cart with real-time item count and total calculation
- **Responsive Design**: Mobile-friendly interface that adapts to all screen sizes
- **Product Search**: Quick search functionality for easy product discovery
- **Smooth Navigation**: Intuitive navigation with scroll-to-section features
- **Customer Reviews**: Display of customer testimonials
- **Blog Section**: Information and updates about products

## Technologies Used

- **HTML5**: Structure and content
- **CSS3**: Styling and animations
- **JavaScript**: Interactive functionality
- **Swiper.js**: Product slider/carousel
- **Font Awesome**: Icons
- **Ionicons**: Additional icons for login forms
- **Google Fonts (Poppins)**: Typography

## Project Structure

```
Grocy-project/
│
├── index.html              # Main homepage
├── Login.html              # Login/Registration page
├── main.js                 # Electron app configuration (optional)
│
├── css/
│   ├── style.css          # Main stylesheet
│   └── style1.css         # Login page stylesheet
│
├── js/
│   ├── script.js          # Main page interactions
│   ├── js1.js             # Login/Register form toggle
│   └── js2.js             # Shopping cart functionality
│
├── images/                 # Product and site images
│   ├── background1.jpg
│   ├── fruits&vegitables1.jpg
│   └── [product images]
│
└── image/                  # Additional images
    ├── cat-1.png to cat-8.png
    ├── feature-img-1.png to feature-img-3.png
    └── blog images
```

## Installation & Setup

1. **Clone or Download** the repository to your local machine

2. **Open the project**:
   - Navigate to the project folder
   - Open `Login.html` to start with the login page
   - Or open `index.html` directly to view the main store

3. **No build process required** - This is a static website that runs directly in the browser

## Usage

### For Customers:

1. **Login/Register**: Start at `Login.html` to create an account or login
2. **Browse Products**: Navigate through different categories
3. **Add to Cart**: Click "add to cart" on any product
4. **View Cart**: Click the cart icon to see selected items and total
5. **Remove Items**: Click the trash icon to remove items from cart

### Navigation:

- **Home**: Landing section with main banner
- **Categories**: Browse by product category
- **Products**: View all available products
- **Features**: Learn about store features
- **Reviews**: Read customer testimonials
- **Blogs**: Read articles about products and healthy living

## Key Features Explained

### Shopping Cart System
- Real-time item count displayed on cart icon
- Dynamic total price calculation
- Add/remove items with instant updates
- Smooth scroll with temporary scrollbar visibility

### Responsive Design Breakpoints
- **Desktop**: Full layout (> 991px)
- **Tablet**: Optimized layout (768px - 991px)
- **Mobile**: Compact menu and adjusted sizing (< 768px)

### Product Slider
- Auto-rotating product showcase
- Touch/swipe enabled on mobile devices
- Configurable slides per view based on screen size

## Customization

### Update Products:
Edit the product sections in `index.html` to add/remove/modify products:
```html
<div class="swiper-slide box">
    <img src="path/to/image.jpg" alt="">
    <h3>Product Name</h3>
    <div class="price">
        <pre>Quantity:1kg   ₹Price/-</pre>
    </div>
    <a href="#" class="btn add-to-cart" data-name="Product Name" data-price="Price">add to cart</a>
</div>
```

### Change Colors:
Modify CSS variables in `css/style.css`:
```css
:root {
    --orange: rgb(100, 207, 73);  /* Primary color */
    --black: #130f40;              /* Text color */
    --light-color: #666;           /* Secondary text */
}
```

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## Known Issues & Limitations

- Shopping cart data is not persistent (resets on page reload)
- No backend integration - purely frontend demonstration
- Payment integration not implemented (checkout is non-functional)
- Some image paths use absolute paths - may need adjustment based on deployment

## Future Enhancements

- [ ] Backend integration with database
- [ ] User authentication with secure login
- [ ] Payment gateway integration
- [ ] Order history and tracking
- [ ] Product filtering and advanced search
- [ ] Wishlist functionality
- [ ] Email notifications
- [ ] Admin panel for product management

## Credits

**Created by Team**:
- Dinesh Veera Bhargav A
- Balla Kumar Basavaraju (balla.raja78@gmail.com)
- V. Teja
- V. Yasaswi


**Note**: This is a practice project designed to demonstrate frontend web development skills. All product prices and information are for demonstration purposes only.
