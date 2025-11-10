# HelloWorld2

This repository contains two main components:

## 1. Android Application - Hello World

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

## 2. PEFA Kabuku Church Website

### Overview
A modern, responsive website for PEFA Kabuku Church built with HTML, CSS (Tailwind CSS), and JavaScript.

### Features

#### Pages
1. **Home Page** (`index.html`)
   - Slideshow header with church images
   - Welcome section
   - Vision & Mission statements (PEFA Kenya Vision, Kabuku Vision, and Mission)
   - Impact statistics (500+ Members, 4 Weekly Services, 20+ Community Projects, 10+ Youth & Kids Groups)
   - Five Strategic Pillars with interactive hover effects and Bible verses
   - Recent Achievements section (Conferences, COVID-19 Relief, Youth Programs)
   - Contact information and social media links

2. **About Page** (`about.html`)
   - Church leadership team structure
   - Senior Pastor section
   - Associate Pastors
   - Church Board members
   - Ministry Leaders
   - Call to action for joining ministry team

3. **Gallery Page** (`gallery.html`)
   - Photo gallery of church events and activities

4. **History Page** (`history.html`)
   - Historical information about the church

#### Interactive Features
- **Responsive Navigation Bar** with dropdown menu for About section
- **Give Modal**: M-Pesa Paybill integration for donations with copy-to-clipboard functionality
- **Image Slideshow**: Automatic rotating slideshow on the homepage (4-second intervals)
- **Interactive Cards**: Hover effects on strategic pillars and achievements revealing additional information
- **Social Media Integration**: Links to Facebook and Instagram

#### Design
- **Framework**: Tailwind CSS (via CDN)
- **Color Scheme**: Sky blue primary color (#0ea5e9) with white and gray accents
- **Typography**: Modern sans-serif font
- **Responsive**: Mobile-first design with responsive grid layouts

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
├── app/                          # Android application
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/            # Java source files
│   │   │   ├── res/             # Android resources
│   │   │   └── AndroidManifest.xml
│   │   ├── androidTest/         # Android instrumentation tests
│   │   └── test/                # Unit tests
│   └── build.gradle             # App-level Gradle build file
├── assets/                       # Website assets (images, logos)
├── docs/                         # Documentation files
├── gradle/                       # Gradle wrapper files
├── index.html                    # Church website homepage
├── about.html                    # About/Team page
├── gallery.html                  # Photo gallery page
├── history.html                  # Church history page
├── build.gradle                  # Project-level Gradle build file
├── settings.gradle               # Gradle settings
└── gradlew                       # Gradle wrapper script
```

## Getting Started

### Android App
1. Open the project in Android Studio
2. Sync Gradle files
3. Run the app on an emulator or physical device

### Website
1. Open `index.html` in a web browser
2. Navigate through the pages using the navigation menu
3. For local development, use a local web server to serve the HTML files

## License
This project appears to be a demonstration/learning project combining Android development with web development for a church organization.
