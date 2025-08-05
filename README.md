🌐 AI Travel Planner
This is an AI-powered web application that generates custom travel itineraries based on user preferences. The project leverages Google's Gemini API to create detailed and personalized travel plans. It also includes an integration with SerpAPI to fetch real-time flight information, if requested.

✨ Features
AI-Powered Itinerary: Generates a detailed travel plan based on user inputs such as destination, dates, budget, and interests.

Customizable Preferences: Allows users to input all necessary information for their trip to get a tailored plan.

Live Flight Information: Integrates with SerpAPI to display real flight options as part of the itinerary.

Modern UI: A clean and responsive user interface built with shadcn-ui and Tailwind CSS.

🛠️ Technologies Used
Frontend: React

Build Tool: Vite

Language: TypeScript

Styling: Tailwind CSS

UI Components: shadcn-ui

APIs:

Google Gemini API: For AI-driven travel plan generation.

SerpAPI: For fetching live flight data.

🚀 Getting Started
To run this project locally, you need to have the following installed:

Node.js and npm

Git

Install Dependencies:

Bash

npm install

Set up API Keys:

This project requires API keys for both Gemini and SerpAPI.

Create a new file named .env in the root of your project directory.

Add your API keys to this file in the following format:

Bash

VITE_GEMINI_API_KEY="YOUR_GEMINI_API_KEY"
VITE_SERPAPI_API_KEY="YOUR_SERPAPI_API_KEY"
Important: Do not commit your .env file to GitHub. Add .env to your .gitignore file.

Run the Project:

Bash

npm run dev
The project will be live at http://localhost:5173.

📝 License
This project is licensed under the MIT License.

