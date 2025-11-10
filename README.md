# PEFA Kabuku Church Website

A modern, responsive website for PEFA Kabuku Church built with HTML, CSS (Tailwind CSS), and JavaScript. This repository showcases a professional church website with fluid animations, enhanced visuals, and excellent user experience.

## Primary Focus: Church Website

This repository is primarily focused on the PEFA Kabuku Church website, providing an engaging online presence for the church community.

---

## Additional Component: Android Application - Hello World

### Overview
A simple Android application that demonstrates the basic structure of an Android app using the Android Support Library and Material Design components.

### Features
- **Main Activity**: `Sayhelloworld` - A basic activity with a toolbar and floating action button
- **Display**: Shows "Hello World!" text in the center of the screen
- **Material Design**: Uses Material Design components including:
  - Toolbar with action bar
  - Floating Action Button (FAB) with email icon
  - Snackbar for displaying messages
- **Menu**: Settings option in the action bar

### Technical Stack
- **Language**: Java
- **Package**: `com.example.android.helloworld`
- **Android Support Libraries**:
  - `android.support.design` for Material Design components
  - `android.support.v7` for AppCompat and Toolbar
  - `android.support.constraint` for ConstraintLayout

### App Structure
- **Activity**: `Sayhelloworld.java` - Main activity class
- **Layouts**:
  - `activity_sayhelloworld.xml` - Main activity layout with CoordinatorLayout
  - `content_sayhelloworld.xml` - Content layout with "Hello World!" TextView
- **Resources**:
  - App name: "Hello World"
  - Menu with Settings option

### Purpose
This is a template/starter Android application that demonstrates:
- Basic Android app structure
- Material Design implementation
- Toolbar and FloatingActionButton usage
- Menu integration
- Proper layout organization

---

## PEFA Kabuku Church Website - Detailed Documentation

### Overview
A professionally designed, modern, and responsive website for PEFA Kabuku Church. The website features fluid animations, gradient backgrounds, enhanced typography, and an engaging user experience across all pages.

### Recent Enhancements (2025)

The website has been significantly enhanced with modern design principles:

#### Visual Improvements
- **Fluid Animations**: Smooth fade-in effects, hover lifts, and transition animations throughout
- **Gradient Backgrounds**: Beautiful gradient overlays and background effects
- **Enhanced Typography**: Improved font hierarchy with better spacing and readability
- **Professional Cards**: Shadow effects, rounded corners, and hover animations on all card elements
- **Consistent Styling**: Unified design language across all pages with `styles.css`

#### Technical Improvements
- **Custom CSS Framework**: Comprehensive `styles.css` with reusable classes for animations and effects
- **Smooth Scroll**: Enhanced navigation with smooth scrolling behavior
- **Accessibility**: Improved focus states, reduced motion support, and semantic HTML
- **Responsive Design**: Enhanced mobile-first approach with better breakpoints
- **Performance**: Optimized animations using CSS transforms and GPU acceleration

### Pages

1. **Home Page** (`index.html`)
   - **Enhanced Slideshow Header**: Smooth transitions with gradient overlay and call-to-action button
   - **Welcome Section**: Expanded content with fade-in animations
   - **Vision & Mission Cards**: Gradient icon backgrounds, larger icons, enhanced hover effects
   - **Impact Statistics**: Colorful gradient cards with improved spacing and larger fonts
   - **Five Strategic Pillars**: Interactive hover effects revealing Bible verses with gradient backgrounds
   - **Recent Achievements**: Enhanced cards with gradient icons and detailed hover overlays
   - **Modern Footer**: Gradient background with improved spacing

2. **About Page** (`about.html`)
   - **Gradient Header**: Eye-catching animated gradient background
   - **Leadership Sections**: Enhanced cards with shadow effects and hover animations
   - **Team Cards**: Gradient placeholders for photos, better spacing, professional layout
   - **Board & Ministry Leaders**: Improved grid layout with consistent styling
   - **Call to Action**: Enhanced CTA section with gradient background

3. **Gallery Page** (`gallery.html`)
   - **Enhanced Filter Buttons**: Gradient active states, shadow effects, smooth transitions
   - **Improved Grid Layout**: Better spacing and hover effects on gallery items
   - **Image Hover Effects**: Scale and overlay animations on hover
   - **Animated Filtering**: Staggered fade-in when filtering categories
   - **Share Section**: Enhanced call-to-action with gradient background

4. **History Page** (`history.html`)
   - **Visual Timeline**: Colorful timeline with gradient markers and connecting line
   - **Enhanced Timeline Cards**: Shadow effects, hover animations, better spacing
   - **Heritage Cards**: Improved layout with gradient backgrounds
   - **Milestone Statistics**: Large, colorful cards with gradient backgrounds
   - **Testimonial Cards**: Professional styling with better typography
   - **Future Vision**: Striking gradient card with animated background

#### Interactive Features
- **Responsive Navigation Bar**: Smooth dropdown menu for About section with fade effects
- **Give Modal**: M-Pesa Paybill integration for donations with copy-to-clipboard functionality and slide-up animation
- **Image Slideshow**: Smooth automatic rotating slideshow on the homepage (4-second intervals)
- **Interactive Cards**: Enhanced hover effects with lift animations and shadow transitions
- **Strategic Pillars**: Hover to reveal Bible verses with smooth opacity transitions
- **Gallery Filtering**: Smooth category filtering with fade-in animations
- **Social Media Integration**: Animated links to Facebook and Instagram

#### Design System
- **Framework**: Tailwind CSS (via CDN) + Custom CSS (`styles.css`)
- **Color Scheme**: 
  - Primary: Sky blue (#0ea5e9) with gradient variations
  - Secondary: Green, Purple, Orange, Blue gradients for different sections
  - Backgrounds: Gradient overlays from gray-50 to gray-100
- **Typography**: 
  - Headers: Bold, large sizes with negative letter-spacing
  - Body: 1.7 line-height for readability, 1.125rem (18px) for important text
  - Shadows: Text shadows on hero sections for contrast
- **Animations**:
  - Fade-in: Staggered entrance animations (0.1s - 0.6s delays)
  - Hover Lift: translateY(-8px) with scale(1.02)
  - Smooth Transitions: 0.3s cubic-bezier timing
  - Floating Elements: 6s ease-in-out infinite
- **Responsive**: Mobile-first design with md: and lg: breakpoints
- **Accessibility**: 
  - Focus states with 2px sky-500 outline
  - Reduced motion support
  - Semantic HTML structure

#### Church Vision & Mission
- **PEFA Kenya Vision**: "Knowing Christ and making Him known."
- **Kabuku Vision**: "Build, grow, and sustain wholesome, Christ-centred members and community."
- **Mission**: "To disciple, care for, and equip believers to live Christ-centred lives that impact our community and beyond."

#### Strategic Pillars
1. Christ-Centredness & Spiritual Formation (2 Peter 3:18)
2. Member Care & Community Building (Galatians 6:2)
3. Excellence & Stewardship (Colossians 3:23)
4. Growth & Multiplication (Matthew 28:19)
5. Governance & Leadership Excellence (Matthew 20:26)

### Contact Information
- **Email**: info@pefakabuku.org
- **Phone**: +254-000-000-000
- **M-Pesa Paybill**: 1234567
- **M-Pesa Account**: 123445678

---

## Repository Structure

```
HelloWorld2/
├── app/                          # Android application (secondary component)
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/            # Java source files
│   │   │   ├── res/             # Android resources
│   │   │   └── AndroidManifest.xml
│   │   ├── androidTest/         # Android instrumentation tests
│   │   └── test/                # Unit tests
│   └── build.gradle             # App-level Gradle build file
├── assets/                       # Website assets (images, logos)
│   ├── Logo.png                 # Church logo
│   ├── Church Empty.jpg         # Church interior photos
│   ├── church-service.jpg
│   ├── church-community.jpg
│   └── church-youth.jpg
├── docs/                         # Documentation files
├── gradle/                       # Gradle wrapper files
├── index.html                    # Church website homepage (primary)
├── about.html                    # About/Team page
├── gallery.html                  # Photo gallery page
├── history.html                  # Church history page
├── styles.css                    # Custom CSS with animations and enhancements
├── favicon.ico.png               # Website favicon
├── build.gradle                  # Project-level Gradle build file
├── settings.gradle               # Gradle settings
├── gradlew                       # Gradle wrapper script
└── README.md                     # This file
```

## Getting Started

### Church Website (Primary)

#### Quick Start
1. Clone the repository
2. Open `index.html` in a modern web browser
3. Navigate through the pages using the navigation menu

#### Local Development Server
For the best experience with all features:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (with http-server package)
npx http-server -p 8000

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000/index.html` in your browser.

#### Customization
1. **Update Church Information**: Edit the HTML files to replace placeholder content
2. **Add Photos**: Place images in the `assets/` directory
3. **Customize Colors**: Modify gradient colors in `styles.css` and Tailwind classes
4. **Adjust Animations**: Edit animation timing and effects in `styles.css`

### Android App (Secondary Component)
1. Open the project in Android Studio
2. Sync Gradle files
3. Run the app on an emulator or physical device

## Browser Compatibility
The website is optimized for modern browsers:
- Chrome/Edge (v90+)
- Firefox (v88+)
- Safari (v14+)
- Opera (v76+)

## Technologies Used
- **HTML5**: Semantic markup
- **CSS3**: Custom animations, transitions, gradients
- **Tailwind CSS**: Utility-first CSS framework
- **JavaScript (Vanilla)**: Interactive features and DOM manipulation
- **Responsive Design**: Mobile-first approach

## Screenshots

### Homepage
![Enhanced Homepage](https://github.com/user-attachments/assets/e866afb3-174d-42cc-a384-be22dfd8fd5b)

### About Page
![Enhanced About Page](https://github.com/user-attachments/assets/f3930056-8028-44e8-b3cd-d709870216d1)

## Future Enhancements
- [ ] Add actual church photos to replace placeholders
- [ ] Implement blog/news section for church updates
- [ ] Add event calendar integration
- [ ] Create sermon archive with audio/video
- [ ] Add multi-language support (English/Swahili)
- [ ] Implement prayer request form
- [ ] Add live streaming capability

## Contributing
This is a church website project. For contributions or suggestions, please contact the church administration at info@pefakabuku.org.

## License
This project is created for PEFA Kabuku Church. All rights reserved.
