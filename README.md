# CoinSight - Your Crypto Vision

A modern, responsive cryptocurrency trading platform website built with HTML, CSS, and vanilla JavaScript. CoinSight provides users with real-time market data, portfolio tracking, educational resources, and financial tools.

## 🚀 Features

### Core Pages
- **Homepage** - Hero section with call-to-action and service overview
- **Dashboard** - Portfolio overview, market data, and quick actions
- **Markets** - Live cryptocurrency prices and market information
- **About** - Company mission, team, and community links
- **Services** - Complete suite of crypto trading tools
- **Pricing** - Transparent pricing plans (Basic, Pro, Enterprise)
- **Learn** - Educational content, guides, and crypto glossary
- **Tools** - Interactive budget calculator

### Key Highlights
- ✨ Modern glassmorphic design with gradient accents
- 📱 Fully responsive mobile-first design
- 🎨 Custom CSS with CSS variables for theming
- 🔒 Security-focused messaging (FIU registered, ISO certified)
- 📊 Real-time market data display
- 🧮 Interactive budget calculator tool
- 🎯 Clean, accessible navigation

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid, Flexbox, animations
- **JavaScript** - (Ready for interactive features)
- **Google Fonts** - Inter font family

## 📁 Project Structure

```
coinsight/
│
├── index.html          # Homepage
├── dashboard.html      # User dashboard
├── markets.html        # Market overview
├── about.html          # About page
├── services.html       # Services page
├── pricing.html        # Pricing plans
├── learn.html          # Educational content
├── tools.html          # Financial tools
│
├── assets/
│   └── css/
│       └── style.css   # Main stylesheet
│
└── images/
    ├── 1.jpg           # Logo
    ├── 2.jpg           # Telegram icon
    ├── 4.png           # YouTube icon
    └── 5.png           # LinkedIn icon
```

## 🎨 Design System

### Color Palette
- **Background Dark**: `rgb(2, 4, 10)`
- **Card Background**: `rgb(18, 24, 41)`
- **Accent Blue**: `#4169E1`
- **Accent Cyan**: `#5F85F5`
- **Positive (Green)**: `#22c55e`
- **Negative (Red)**: `#ef4444`

### Typography
- **Font Family**: Inter
- **Weights**: 400 (Regular), 600 (Semi-bold), 700 (Bold), 800 (Extra-bold)

### Spacing
- Border radius: 8px, 12px, 16px
- Container max-width: Responsive
- Grid gaps: 1.75rem - 2rem

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/coinsight.git
   cd coinsight
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js (with http-server)
   npx http-server
   ```

3. **Navigate to `http://localhost:8000`**

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 992px
- **Desktop**: > 992px

## 🔧 Customization

### Changing Colors
Edit CSS variables in `style.css`:
```css
:root {
    --accent-blue: #4169E1;
    --accent-cyan: #5F85F5;
    /* Add your colors */
}
```

### Adding New Pages
1. Create new HTML file
2. Copy navigation structure from existing pages
3. Update active navigation link
4. Add new page to footer sitemap

## 🌟 Key Components

### Navigation
- Fixed position navbar with glassmorphic effect
- Mobile hamburger menu
- Active page highlighting

### Cards
- Glassmorphic background
- Hover effects with elevation
- Border glow on hover

### Forms
- Custom styled inputs
- Focus states with accent colors
- Full-width responsive design

## 📊 Budget Calculator

The tools page includes an interactive budget calculator that:
- Accepts monthly income and expenses
- Calculates remaining budget
- Displays results in a visual donut chart
- Shows breakdown with color-coded legend

## 🔒 Security Features Highlighted      

- FIU (Financial Intelligence Unit) registered
- ISO/IEC 27001:2022 certified
- Multi-signature wallets
- Cold storage solutions
- 24/7 customer support

## 📈 Future Enhancements

- [ ] Add JavaScript functionality for budget calculator
- [ ] Implement real-time cryptocurrency price API
- [ ] Add user authentication system
- [ ] Create interactive trading charts
- [ ] Build portfolio tracking functionality
- [ ] Add dark/light theme toggle
- [ ] Implement search functionality
- [ ] Add blog/news section with CMS

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Team

- **Aryan Goyal** - Co-Founder & CEO

## 🙏 Acknowledgments

- Inter font by Rasmus Andersson
- Icons and imagery for demonstration purposes
- Inspired by modern fintech design patterns

---

**Built with ❤️ for the crypto community**

© 2025 CoinSight. All rights reserved.