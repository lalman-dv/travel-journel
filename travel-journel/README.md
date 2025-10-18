🌍 Travel Journal React Project

Welcome to my Travel Journal project! This is a simple React app that showcases some of the most memorable places I've visited—Boracay Island 🇵🇭, Singapore 🇸🇬, and Kuala Lumpur 🇲🇾. Each entry includes a photo, travel dates, a short description, and a Google Maps link to the location.

🚀 What I Learned

This project was a hands-on way for me to explore key React concepts:

✅ Props

• I learned how to pass data from a parent component to child components using props.
• Each travel entry is rendered using a reusable Card component that receives props like title, image, dates, and description.

✅ `.map()` in React

• I used the .map() method to dynamically render multiple travel cards from a single data array.
• This helped me understand how to iterate over data and generate JSX elements efficiently.

🧱 Tech Stack

• React (Functional Components)
• JavaScript (ES6+)
• CSS (for basic styling)
• Google Maps Links (for location references)

📁 Project Structure
src/
├── App.jsx
├── data.js // Contains travel data
├── Entry.jsx // Reusable component for each travel entry
├── index.jsx
└── index.css

✨ Features

• Clean layout with travel cards
• Dynamic rendering using .map()
• Props-driven component architecture
• External image and map links for each location

📸 Sample Screenshot

🛠️ How to Run

1.  Clone the repo
2.  Run npm install
3.  Start the app with npm start

🧠 Next Steps

• Add more destinations
• Include user input to add new entries
• Improve styling with CSS modules or Tailwind
• Add animations or transitions
