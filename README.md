# Travel-Mate
TravelMate AI is a modern, responsive travel discovery web application designed to help users explore destinations, hotels, restaurants, beaches, temples, parks, and activities in one place
✨ Features
🌍 Explore travel destinations
🏨 Discover hotels and resorts
🏠 Explore residences and villas
🍴 Find restaurants and food experiences
🏖️ Discover beaches
🛕 Explore temples and landmarks
🌳 Discover parks and nature locations
🤿 Explore travel activities
🔎 Travel destination and category search
📍 Current location detection
❤️ Favorites interaction
🤖 AI Travel Assistant
🧳 AI-powered trip planning interface
📱 Responsive design for desktop and mobile
✨ Smooth hover and click animations
🎨 Modern premium travel UI
⚡ Dynamic content rendering with JavaScript
🛠️ Technologies Used
HTML5
CSS3
JavaScript
Geolocation API
Fetch API
Claude AI API integration
Unsplash Images
📂 Project Structure
travelmate-ai/
│
├── index.html
├── README.md
└── assets/
    └── images/

The current project is implemented as a single HTML file containing the page structure, styling, and JavaScript functionality.

🚀 Main Sections
🏠 Home

The homepage provides a travel-focused hero section with:

TravelMate branding
Destination search
Explore destinations button
AI assistant button
Location detection
🌎 Destinations

Users can explore destinations such as:

Maldives
Goa
Bali

The project also provides category-based travel discovery.

🏨 Travel Categories

TravelMate includes:

Destinations
Hotels
Residencies
Restaurants
Beaches
Temples
Parks
Activities
🤖 TravelMate AI

The application includes an AI chat interface where users can ask travel-related questions such as:

Find hotels in Goa.
Show me beaches near me.
Plan a 3 day Bali trip.
Find a luxury resort.

The frontend sends AI requests to:

/api/claude

The backend/API configuration is required for the AI functionality to work.

📍 Location Detection

TravelMate uses the browser's Geolocation API to request the user's current coordinates.

The application asks the browser for permission before accessing location information.

🔎 Search

Users can search for travel categories and destinations directly from the homepage.

Examples:

Goa
Bali
Maldives
Hotels
Restaurants
Beaches
Temples
Parks
Activities
🎨 UI/UX

The interface focuses on a premium travel experience with:

Responsive layouts
Glass-style navigation
Animated cards
Hover effects
Dynamic pages
Travel imagery
Floating AI assistant
Smooth transitions
Mobile-friendly layouts
▶️ How to Run
1. Clone the repository
git clone https://github.com/YOUR-USERNAME/travelmate-ai.git
2. Open the project

Open:

index.html

in your browser.

For the best experience, run it using a local development server such as VS Code Live Server.

⚠️ AI Configuration

The frontend expects an API endpoint:

/api/claude

The AI assistant will not work correctly unless a backend is configured for this endpoint.

Do not upload API keys or secret credentials to GitHub.

Use environment variables on the backend for private API credentials.

🔮 Future Improvements
🗺️ Interactive maps
📍 Nearby places based on location
🏨 Real hotel availability
🍴 Restaurant recommendations
✈️ Flight search
🧳 Complete itinerary generation
🌦️ Weather information
⭐ User reviews and ratings
🔐 User authentication
💾 Database integration
❤️ Cloud-saved favorites
📱 Progressive Web App support
🤖 More advanced AI trip planning
📸 Project Preview

Add screenshots of the TravelMate interface here:

screenshots/
├── home.png
├── destinations.png
├── categories.png
└── ai-assistant.png
👨‍💻 Author

Your Name

TravelMate AI — Travel Discovery Web Application

📄 License

This project is available for educational and personal project purposes.
