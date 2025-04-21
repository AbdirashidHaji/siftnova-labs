Modern, responsive website for a software development company

Table of Contents
Features

Technologies Used

Installation

Project Structure

Customization

Browser Support

License

Credits

Features ✨
Responsive Design
Fully adaptive layout for all devices (mobile, tablet, desktop)

Mobile-first approach with progressive enhancement

Flexible grid and card components

Modern UI Components
Interactive service tabs with smooth transitions

Testimonial carousel

Contact form with validation

Back-to-top floating button

Animated mobile navigation

Performance Optimized
Lightweight (under 500KB total)

Fast-loading assets

Minimal dependencies

Developer Friendly
Clean, semantic HTML5

Tailwind CSS utility classes

Well-commented JavaScript

Easy-to-modify structure

Technologies Used 🛠️
Core:

HTML5

CSS3

JavaScript

Frameworks & Libraries:

Tailwind CSS

Remix Icons

Fonts:

Inter (Google Fonts)

Pacifico (Logo font)

Installation 💻
Clone the repository

bash
git clone https://github.com/yourusername/softnova-labs.git
cd softnova-labs
Open in browser

Double-click index.html or

Use Live Server extension in VS Code

For development

Install Tailwind CSS (if modifying styles)

bash
npm install -D tailwindcss
npx tailwindcss init
Project Structure 📂
softnova-labs/
├── index.html              # Main website file
├── css/
│   └── styles.css          # Additional custom styles
├── js/
│   └── script.js           # Interactive functionality
├── images/                 # All visual assets
│   ├── hero-bg.jpg         # Hero section background
│   ├── service-dev.jpg     # Services image
│   └── team/               # Team member photos
├── README.md               # This documentation
└── .gitignore              # Git exclusion rules
Customization 🎨
Change Colors:

html
<script>
  tailwind.config = {
    theme: {
      extend: {
        colors: {
          primary: '#your-hex-code',  // Main brand color
          secondary: '#your-hex-code' // Secondary color
        }
      }
    }
  }
</script>
Update Content:

Replace placeholder text in HTML

Add/remove feature cards in the Features section

Modify the services tabs in the Services section

Browser Support 🌐
Browser	Version	Status
Chrome	90+	✅
Firefox	88+	✅
Safari	14+	✅
Edge	91+	✅
Mobile	iOS/Android	✅
License 📜
This project is licensed under the MIT License - see the LICENSE file for details.

Credits 🙏
Hero image from Unsplash

Icons by Remix Icon

Fonts from Google Fonts

Happy Coding! 🚀