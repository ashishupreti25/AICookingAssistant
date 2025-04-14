# AICookingAssistant

README: AI Cooking Assistant
Overview
The AI Cooking Assistant is a Streamlit-based application designed to assist users in the kitchen by leveraging AI-powered tools. It provides two main functionalities:

YouTube Cooking Assistant: Summarizes YouTube cooking videos into step-by-step instructions and ingredient lists.
Image-Based Recipe Suggestions: Identifies ingredients from uploaded images and suggests possible recipes.
This application is powered by Google GenAI and uses the Gemini API for generating content. It is ideal for home cooks, food enthusiasts, and anyone looking to simplify their cooking experience.

Features
1. YouTube Cooking Assistant
Functionality:
Users can input a YouTube video URL of a cooking tutorial.
The app summarizes the video into clear cooking instructions and an ingredient list.
Use Case:
Quickly extract actionable steps from long cooking videos without watching the entire video.
How It Works:
The app uses the Gemini API to analyze the video and generate a structured summary.
2. Image-Based Recipe Suggestions
Functionality:
Users can upload an image of ingredients or a dish.
The app identifies the ingredients in the image and suggests possible recipes.
Use Case:
Discover recipes based on available ingredients or identify dishes from an image.
How It Works:
The app processes the uploaded image and uses the Gemini API to generate ingredient lists and recipe suggestions.
Project Structure
Main File
CookingAssistant.py: The main application file that handles the Streamlit UI and integrates with the Gemini API.
Key Components
YouTube Cooking Assistant:
Input: YouTube video URL.
Output: Cooking instructions and ingredient list.
Image-Based Recipe Suggestions:
Input: Uploaded image.
Output: Identified ingredients and suggested recipes.
Setup and Installation
Prerequisites
Python 3.8 or higher
pip (Python package manager)
Installation Steps
Clone the repository:

Install the required dependencies:

Set up the environment variables:

Create a .env file in the root directory.
Add your Gemini API key:
Run the application:

Usage
1. Launch the App
Open the app in your browser after running the streamlit command.
The home page will display the title "🍳 AI Cooking Companion" with a sidebar menu.
2. Select a Feature
Use the sidebar to choose between:
YouTube Cooking Assistant
Image-Based Recipe Suggestions
3. Follow the Instructions
YouTube Cooking Assistant:
Enter a YouTube video URL.
Click "Generate Instructions" to get a summary of the video.
View the cooking instructions and ingredient list.
Image-Based Recipe Suggestions:
Upload an image of ingredients or a dish.
Click "Get Ingredients & Recipe Suggestions" to identify ingredients and view recipe suggestions.
Example Use Cases
1. Summarizing a YouTube Cooking Video
Scenario: You find a 20-minute cooking video but only need the recipe and steps.
Steps:
Enter the YouTube video URL.
Click "Generate Instructions."
View the summarized instructions and ingredient list.
Example:
Input: YouTube URL of a pasta recipe.
Output:
Instructions: Step-by-step guide to making pasta.
Ingredients: List of required ingredients.
2. Identifying Ingredients from an Image
Scenario: You have a picture of ingredients and want to know what you can cook.
Steps:
Upload the image.
Click "Get Ingredients & Recipe Suggestions."
View the identified ingredients and suggested recipes.
Example:
Input: Image of tomatoes, onions, and garlic.
Output:
Ingredients: Tomatoes, onions, garlic.
Recipes: Tomato soup, pasta sauce, salsa.
Styling and Aesthetics
Custom Styling
The app uses a custom font ("Roboto") for a clean and modern look.
Buttons and menus are styled for ease of use.
User-Friendly Interface
Sidebar navigation for quick access to features.
Loading spinners for long-running tasks.
Clear error messages for invalid inputs.
Future Enhancements
Add support for more file types (e.g., .docx, .csv).
Integrate additional AI models for better accuracy.
Provide multilingual support for instructions and recipes.
Add a feature for generating meal plans based on available ingredients.
Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For questions or feedback, please contact:

Ashish: ashish_upreti7@yahoo.com
Enjoy using the AI Cooking Assistant! 🍳✨---
