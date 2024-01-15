# Openai-api
 YouTube Audio Summarizer and Meels Plan
 
# OpenAI API Project

This project utilizes the OpenAI API to perform various tasks, including generating meal plans and creating summaries for transcribed audio. The functionality is exposed through a FastAPI web application, making it easy for users to interact with the OpenAI-powered features.

## Features

1. **Meal Plan Generation:**
   - **Endpoint:** `/meals_plan`
   - **Description:** Takes user-specified ingredients and caloric preferences, generates three meals with titles and recipes, and returns the meal plan.

2. **Image Generation for Meals:**
   - **Endpoint:** `/generate_images`
   - **Description:** Utilizes the OpenAI DALL-E API to create images for each meal based on the generated titles. The images are then packaged into a downloadable zip file.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Ammar-Abdelhady-ai/Openai-api.git
