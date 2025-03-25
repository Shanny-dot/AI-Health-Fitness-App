# AI-Health-Fitness-App

The **AI Health & Fitness Planner** is a personalized health and fitness agent built using the Agno AI Agent framework. This application creates tailored dietary and fitness plans based on user inputs like age, weight, height, activity level, dietary preferences, and fitness goals.

## Features

- **Dual AI Agents**  
  - **Health Agent**: Specializes in dietary advice and meal planning.  
  - **Fitness Agent**: Focuses on workout routines and exercise guidance.

- **Personalized Dietary Plans**  
  - Generates detailed meal plans including breakfast, lunch, dinner, and snacks.  
  - Considers hydration, electrolytes, fiber intake, and other nutritional essentials.  
  - Supports dietary preferences such as Keto, Vegetarian, Low Carb, and more.

- **Personalized Fitness Plans**  
  - Designs custom exercise routines tailored to your fitness goals.  
  - Includes warm-ups, main workouts, and cool-downs.  
  - Offers actionable fitness tips and suggestions for tracking progress.

- **Interactive Q&A**  
  - Ask follow-up questions to refine or clarify your diet and fitness plans.

## Requirements

The application depends on the following Python libraries:  
- `agno`  
- `google-generativeai`  
- `streamlit`  

Install these dependencies using the versions specified in the `requirements.txt` file.

## How to Run

Follow these steps to set up and run the AI Health & Fitness Planner:

1. **Get a Gemini API Key**  
   - Obtain a free API key from Google AI Studio: [https://aistudio.google.com/apikey](https://aistudio.google.com/apikey).  
   - You'll need this key to power the app's AI features.

2. **Clone the Repository**  
   ```bash
   git clone https://github.com/Shubhamsaboo/awesome-llm-apps.git
   cd awesome-llm-apps/ai_agent_tutorials/ai_health_fitness_agent
