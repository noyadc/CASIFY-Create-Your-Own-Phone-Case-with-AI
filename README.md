# CASIFY-Create-Your-Own-Phone-Case-with-AI
CASIFY is an AI-powered web application that allows users to design personalized phone cases effortlessly. Users can generate unique designs using AI or choose from trendy pre-made templates. The platform also includes a 3D preview system, a virtual assistant, and the ability to showcase or sell designs.

Features:
AI-powered phone case design generation using prompts
Pre-made design library with trendy templates
Real-time 3D preview of phone cases
Virtual assistant (Casify AI) for guidance and suggestions
Option to upload and sell custom designs
Eco-friendly and user-focused customization
Fully responsive interface for desktop and mobile

How It Works
User Input
Enter a design prompt or idea
Or select a pre-made template
AI Processing
The system uses the Hugging Face API to generate images based on the input
Design Preview
The design is applied to a phone case model
Users can view it in an interactive 3D preview
Customization
Users can adjust placement, size, or try different designs
Save or Sell
Save the final design
Option to upload and sell designs
Backend Processing
Data is managed using Supabase

Tech Stack

Frontend:
HTML5
CSS3
JavaScript

Backend:
Python
APIs and Services:
Hugging Face API (for AI image generation)
Supabase (for database, authentication, and storage)

Installation and Setup:

Clone the repository:

git clone https://github.com/your-username/casify.git
cd casify

Backend setup:

pip install -r requirements.txt

Create a .env file:

HUGGINGFACE_API_KEY=your_api_key_here
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key

Run the backend:

python app.py


Frontend setup:
Open index.html in your browser
(or use Live Server in VS Code)

Future Enhancements:
Advanced design editing tools
Integrated payment system
Order tracking system
Improved AI personalization
Mobile application
