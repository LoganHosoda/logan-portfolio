# Logan Hosoda - Portfolio Website

A modern, responsive portfolio website showcasing the work and achievements of Logan Hosoda, a Full Stack Developer specializing in web development and software engineering.

## 🚀 Live Demo

Visit the live portfolio: [Logan Portfolio](https://loganhosoda.github.io/logan-portfolio/)

## 📋 Table of Contents

- [About](#about)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Project Structure](#project-structure)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🎯 About

This portfolio website serves as a comprehensive showcase of Logan Hosoda's professional work, including:

- **8 Featured Projects**: From simple vanilla JavaScript games to complex full-stack applications
- **Professional Achievements**: Technical assessments and certifications
- **Education**: Computer Science specialization from University of Illinois
- **Contact Information**: Professional networking and resume access

## 🛠 Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with CSS Grid and Flexbox
- **Fonts**: Google Fonts (Prompt font family)
- **Icons**: Custom SVG icons
- **Deployment**: GitHub Pages ready

## ✨ Features

### 🎨 Design & UX
- **Responsive Design**: Mobile-first approach with media queries
- **Modern Layout**: CSS Grid and Flexbox for optimal layouts
- **Custom Animations**: Smooth transitions and hover effects
- **Dark Theme**: Professional dark color scheme
- **Typography**: Clean, readable font hierarchy

### 🖥 Navigation
- **Fixed Navigation Bar**: Sticky header with smooth scrolling
- **Social Media Links**: Direct links to GitHub and LinkedIn
- **Resume Access**: One-click resume download
- **Anchor Navigation**: Jump to specific sections

### 📱 Responsive Features
- **Mobile Optimization**: Optimized for screens down to 320px
- **Tablet Support**: Fluid layouts for medium screens
- **Desktop Enhancement**: Enhanced layouts for large screens (1200px+)

### 🎯 Content Sections
- **Hero Section**: Professional introduction with call-to-action
- **Projects Portfolio**: Detailed project showcases with live demos
- **Achievements**: Technical assessments and certifications
- **Contact Footer**: Multiple contact methods

## 📁 Project Structure

```
logan-portfolio/
├── index.html                    # Main HTML file
├── README.md                     # Project documentation
└── src/
    ├── style.css                 # Main stylesheet
    ├── script.js                 # JavaScript functionality
    ├── documents/
    │   └── Logan_Hosoda_Resume_2022.pdf
    └── images/
        ├── Github.svg            # GitHub icon
        ├── Linkedin.svg          # LinkedIn icon
        ├── hero-background.jpg   # Hero section background
        ├── *-certificate-*.png   # Achievement certificates
        ├── *-assessment-*.png    # Technical assessment results
        └── *.png                 # Project screenshots
```

## 🚀 Setup Instructions

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### Local Development

1. **Clone the Repository**
   ```bash
   git clone https://github.com/LoganHosoda/logan-portfolio.git
   cd logan-portfolio
   ```

2. **Open in Browser**
   ```bash
   # Option 1: Direct file opening
   open index.html

   # Option 2: Local server (recommended)
   python -m http.server 8000
   # or
   npx serve .
   ```

3. **View in Browser**
   - Direct: `file:///path/to/logan-portfolio/index.html`
   - Server: `http://localhost:8000`

### Development Setup

For active development with live reload:

```bash
# Using Live Server (VS Code extension)
# or
npx live-server
```

## 💻 Usage

### Viewing the Portfolio
- Navigate through sections using the top navigation menu
- Click project buttons to view GitHub repositories and live demos
- Download resume directly from the hero section
- Connect via social media links in the navigation

### Customization
- **Colors**: Modify CSS variables in `:root` section of `style.css`
- **Content**: Update project information in `index.html`
- **Images**: Replace images in `src/images/` directory
- **Resume**: Update PDF file in `src/documents/`

## 🚀 Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Access via `https://username.github.io/repository-name`

### Netlify
1. Connect GitHub repository to Netlify
2. Build settings: 
   - Build command: (leave empty)
   - Publish directory: `/`
3. Deploy automatically on push

### Vercel
1. Import GitHub repository
2. Framework preset: Other
3. Build and output settings: (leave default)
4. Deploy

## 📈 Featured Projects

The portfolio showcases 8 key projects:

1. **Gaming Moments v2.0** - Next.js social media app with video uploads
2. **E-Commerce Demo** - Full-stack store with Stripe integration
3. **Gaming Moments v1.0** - MERN stack social media application
4. **Technical Assessments** - Front-end and back-end work simulations
5. **iPhone Calculator** - Pixel-perfect calculator replica
6. **Etch-a-Sketch** - Interactive drawing canvas
7. **Tic Tac Toe** - Ruby command-line game

## 🤝 Contributing

This is a personal portfolio project, but suggestions and feedback are welcome!

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -am 'Add improvement'`)
4. Push to branch (`git push origin feature/improvement`)
5. Create Pull Request

### Development Guidelines
- Follow existing code style and structure
- Test responsiveness across devices
- Optimize images for web performance
- Maintain accessibility standards

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**Logan Hosoda**
- **Email**: [loganhosoda@gmail.com](mailto:loganhosoda@gmail.com)
- **Phone**: (509) 964-5926
- **GitHub**: [LoganHosoda](https://github.com/LoganHosoda)
- **LinkedIn**: [Logan Hosoda](https://www.linkedin.com/in/Logan-Hosoda/)

---

## 🏗 Current Development Status

This portfolio is actively maintained and updated. Current priorities include:

- [x] Mobile responsiveness improvements
- [ ] Hamburger menu for mobile navigation
- [ ] Navigation anchor improvements
- [ ] About me section expansion
- [ ] Contact form implementation
- [ ] Footer enhancements
- [ ] Navigation animations
- [ ] Button hover animations
- [ ] Project card animations

**Version**: 0.1+ (Active Development)

---

*Built with ❤️ by Logan Hosoda*