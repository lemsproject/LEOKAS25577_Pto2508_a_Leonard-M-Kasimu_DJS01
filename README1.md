# Podcast App - DJS01 Project

## 📋 Project Overview

A responsive, single-page podcast browsing application built with vanilla JavaScript and React. Users can explore podcast shows, view detailed information in modals, and access a rich catalog of shows without page reloads. The application emphasizes clean code architecture, accessibility, and seamless user experience.

---

## ✨ Key Features

### Landing Page

- **Podcast Grid Display**: Browse all available podcasts at a glance
- **Rich Card Information**: Each podcast card displays:
  - Cover artwork
  - Show title
  - Number of seasons
  - Genre tags
  - Last updated date (human-readable format)
- **Responsive Design**: Optimized for desktop and mobile devices

### Modal Details View

- **Detailed Show Information**: Click any podcast to view comprehensive details
- **Complete Show Metadata**:
  - High-resolution cover image
  - Full podcast description
  - Genre categorization
  - Season information with episode counts
  - Last updated timestamp
- **Accessible Modal**: Easy close functionality with keyboard support

### User Experience

- **No Page Reloads**: Smooth, seamless modal transitions
- **Keyboard Navigation**: Full accessibility with Enter/Space key support
- **Responsive UI**: Consistent experience across all screen sizes

---

## 🏗️ Project Structure

```
├── src/                          # Main application source
│   ├── data.js                   # Podcast dataset
│   ├── index.js                  # Application entry point
│   ├── components/
│   │   ├── createPodcastCard.js  # Podcast card component
│   │   └── createModal.js        # Modal component
│   ├── views/
│   │   └── createGrid.js         # Grid layout management
│   └── utils/
│       ├── DateUtils.js          # Date formatting utilities
│       └── GenreService.js       # Genre management service
├── PodcastApp/                   # React version (Vite setup)
│   ├── src/
│   ├── package.json
│   └── vite.config.js
├── styles.css                    # Global styles
├── index.html                    # Main HTML template
└── wireframe reference images/   # Design mockups
```

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Build Tool**: Vite
- **Framework Options**: React 19 (alternative version)
- **Code Quality**: ESLint configuration included
- **Accessibility**: ARIA labels, semantic HTML, keyboard navigation

---

## 💻 Development Tools

### Available Scripts

```bash
# Development server
npm run dev

# Build for production
npm run build

# Run linter
npm run lint

# Preview production build
npm run preview
```

---

## 🎯 Code Principles

- **Object-Oriented Programming**: Structured classes for services and components
- **Functional Programming**: Modular, reusable functions with clear responsibilities
- **SOLID Design**: Single Responsibility, Open/Closed, and Dependency Inversion principles
- **Clean Code**: JSDoc comments, descriptive naming, and abstracted logic
- **Accessibility First**: WCAG compliance with ARIA attributes and keyboard support

---

## 📱 Responsive Design

The application adapts seamlessly to various screen sizes with dedicated wireframes for:

- Desktop view
- Mobile view
- Tablet compatibility

---

## 🚀 Getting Started

1. **Clone/Download** the project
2. **Install dependencies** (if using React version):
   ```bash
   cd PodcastApp
   npm install
   ```
3. **Run development server**:
   ```bash
   npm run dev
   ```
4. **Open** in browser and start exploring podcasts!

---

## 📚 Notable Implementation Details

- **Date Formatting**: Human-readable relative dates (e.g., "2 weeks ago")
- **Genre Service**: Efficient genre lookup and categorization
- **Modal Architecture**: Clean separation of concerns between modal logic and display
- **Event Handling**: Robust click and keyboard event management
- **Image Management**: Proper alt text and cover image optimization

---

## 📝 Version Notes

- **Vanilla JS Version**: Pure JavaScript implementation with component functions
- **React Version**: Modern React setup using Vite for faster development and build times

---

## 👤 Author

Leonard M Kasimu (LEOKAS25577)

---

**Status**: Complete ✅
