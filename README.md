# 🌱 Paradise Nursery - E-Plant Shopping

A modern, responsive e-commerce web application for plant enthusiasts built with React and Redux Toolkit. Browse through our curated collection of plants across multiple categories and enjoy a seamless shopping experience.

![Paradise Nursery](https://cdn.pixabay.com/photo/2020/08/05/13/12/eco-5465432_1280.png)

## ✨ Features

### 🛍️ Shopping Experience
- **Product Catalog**: Browse 30+ plants across 6 specialized categories
- **Smart Cart System**: Add, remove, and update quantities with real-time calculations
- **Responsive Design**: Optimized for desktop and mobile devices
- **Intuitive Navigation**: Smooth transitions between product listing and cart views

### 🌿 Plant Categories
- **Air Purifying Plants** - Improve your indoor air quality
- **Aromatic Fragrant Plants** - Natural aromatherapy for your space
- **Insect Repellent Plants** - Natural pest control solutions
- **Medicinal Plants** - Traditional healing and wellness plants
- **Low Maintenance Plants** - Perfect for busy lifestyles
- **Drought-Tolerant Plants** - Water-wise gardening options

### 🛒 Cart Features
- Real-time item count display
- Quantity increment/decrement controls
- Individual item removal
- Total cost calculations
- Continue shopping functionality
- Checkout preparation (expandable)

## 🚀 Technologies Used

- **Frontend Framework**: React 18.2.0
- **State Management**: Redux Toolkit 2.2.3 with React-Redux 9.1.1
- **Build Tool**: Vite 5.2.0
- **Styling**: CSS3 with modern flexbox layouts
- **Development**: ESLint for code quality
- **Deployment**: GitHub Pages ready

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/e-plantShopping.git
   cd e-plantShopping
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the application

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint for code quality checks
- `npm run deploy` - Deploy to GitHub Pages

## 📁 Project Structure

```
e-plantShopping/
├── src/
│   ├── components/
│   │   ├── App.jsx           # Main application component
│   │   ├── ProductList.jsx   # Product catalog and display
│   │   ├── CartItem.jsx      # Shopping cart functionality
│   │   └── AboutUs.jsx       # Company information
│   ├── redux/
│   │   ├── store.js          # Redux store configuration
│   │   └── CartSlice.jsx     # Cart state management
│   ├── styles/
│   │   ├── App.css
│   │   ├── ProductList.css
│   │   ├── CartItem.css
│   │   └── AboutUs.css
│   └── main.jsx              # Application entry point
├── public/
│   └── vite.svg
├── package.json
└── vite.config.js
```

## 🎯 Key Components

### Redux State Management
- **CartSlice**: Manages cart items, quantities, and totals
- **Actions**: `addItem`, `removeItem`, `updateQuantity`
- **Selectors**: Real-time cart state access across components

### Product Management
- Categorized plant inventory with images and descriptions
- Dynamic pricing and availability tracking
- Search and filter capabilities (expandable)

### User Interface
- Landing page with company branding
- Smooth page transitions and animations
- Visual feedback for user interactions
- Mobile-responsive design patterns

## 🌟 Usage

1. **Browse Plants**: Start from the landing page and click "Get Started"
2. **Explore Categories**: Navigate through different plant categories
3. **Add to Cart**: Click "Add to Cart" for desired plants
4. **Manage Cart**: View cart, adjust quantities, or remove items
5. **Checkout**: Calculate totals and proceed with purchase

## 🔧 Configuration

### Environment Setup
The application is configured for GitHub Pages deployment with the base path set in `vite.config.js`:

```javascript
export default defineConfig({
  base: "/e-plantShopping",
  plugins: [react()],
})
```

### Redux Store
Cart state is persisted across component renders using Redux Toolkit:

```javascript
const store = configureStore({
  reducer: {
    cart: cartReducer,
  },
});
```

## 🚀 Deployment

This project is configured for GitHub Pages deployment:

1. **Build the project**
   ```bash
   npm run build
   ```

2. **Deploy to GitHub Pages**
   ```bash
   npm run deploy
   ```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 Future Enhancements

- [ ] User authentication and profiles
- [ ] Payment gateway integration
- [ ] Plant care guides and tips
- [ ] Wishlist functionality
- [ ] Product reviews and ratings
- [ ] Search and filter capabilities
- [ ] Order history and tracking
- [ ] Plant care reminders

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Paradise Nursery Development Team**
- *Where Green Meets Serenity*

## 🙏 Acknowledgments

- Plant images sourced from Pixabay and Unsplash
- React and Redux communities for excellent documentation
- Vite team for the lightning-fast build tool

---

*Happy Gardening! 🌱*