# -WanderlustTravel
Interactive travel and ticket booking UI built with HTML/CSS/JS and Tailwind. Features smooth animations, mobile responsiveness, and a Gemini-powered AI assistant.
Interactive travel and ticket booking UI built with HTML/CSS/JS and Tailwind. Features smooth animations, mobile responsiveness, and a Gemini-powered AI assistant.# 🌍 Travel Booking Portal

A modern, comprehensive frontend UI for a travel and ticket booking agency. This portal allows users to search for flights, IRCTC-style train tickets, hotels, and holiday packages. It features a fully responsive design, custom animations, and a built-in AI Travel Assistant.

## ✨ Features

*   **Multi-Booking UI:** Dedicated interfaces for Flights, Trains, Hotels, and Holiday Packages.
*   **Indian Railways (IRCTC) Mock-up:** Realistic train search results with class selection (1A, 2A, 3A, SL, CC) and availability status.
*   **AI Travel Assistant:** A floating chat widget powered by the Gemini API to help users generate custom travel itineraries and get instant advice.
*   **Modern Animations:** Staggered load effects, smooth card hover states, and seamless transitions.
*   **Fully Responsive:** Mobile-first design with horizontal touch-scrolling for complex UI elements like train coach layouts.
*   **Customer Dashboard:** User interface for managing bookings, profiles, and saved trips.

## 🛠️ Tech Stack

*   **HTML5**
*   **CSS3 & Tailwind CSS** (for utility-first styling and keyframe animations)
*   **Vanilla JavaScript** (for interactive components, API calls, and DOM manipulation)
*   **Gemini API** (for the AI chatbot functionality)
*   **Marked.js** (for rendering Markdown in chat responses)

## 📂 Project Structure

\`\`\`text
travel-booking-portal/
│
├── index.html              # Landing Page & Main Search
├── flights.html            # Flight Search Interface
├── trains.html             # Train Booking & Seat Availability
├── hotels.html             # Hotel Search & Filtering
├── packages.html           # Holiday Packages & Tours
├── visa.html               # Visa Services Info
├── dashboard.html          # Customer Portal
├── login.html              # User Authentication
├── register.html           # Account Creation
│
├── css/
│   ├── style.css           # Global styles
│   ├── navbar.css          # Navigation styling & blur effects
│   ├── hero.css            # Hero banner styles
│   ├── booking.css         # Search results & card styles
│   ├── dashboard.css       # User dashboard layouts
│   ├── responsive.css      # Mobile media queries
│   └── animations.css      # Custom keyframes & hover states
│
├── js/
│   ├── app.js              # Core logic & initializations
│   ├── search.js           # Search form handlers
│   ├── slider.js           # Image & content sliders
│   ├── booking.js          # Booking flow & modal logic
│   ├── dashboard.js        # Dashboard interactivity
│   └── api.js              # Gemini AI & backend API calls
│
└── assets/
    ├── images/             
    ├── icons/              
    ├── videos/             
    └── fonts/              
\`\`\`

## 🚀 Getting Started

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/yourusername/travel-booking-portal.git
   \`\`\`
2. Navigate to the project directory:
   \`\`\`bash
   cd travel-booking-portal
   \`\`\`
3. Open `index.html` in your preferred web browser to view the application. (No build process required).

## 💡 Notes for Future Backend Integration

This project is currently a frontend implementation. The UI is structured to be easily integrated with backend frameworks (like WordPress or Frappe) and B2B travel APIs (such as TBO, redBus SeatSeller, or PSPs for IRCTC) to handle live inventory and transactions.
