# OpenAI-API Project

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
  - [Meal Plan Generation](#meal-plan-generation)
  - [Image Generation for Meals](#image-generation-for-meals)
  - [YouTube Audio Summarizer](#youtube-audio-summarizer)
- [Getting Started](#getting-started)
  - [Clone the Repository](#clone-the-repository)
  - [Environment Setup](#environment-setup)
  - [Run the FastAPI App](#run-the-fastapi-app)
- [Scripts Overview](#scripts-overview)
  - [Meals Plan](#meals-plan)
  - [YouTube Audio Summary](#youtube-audio-summary)
- [API Endpoint](#api-endpoint)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This OpenAI-API project combines two key functionalities: generating meal plans and creating summaries for transcribed audio from YouTube videos. The integration of OpenAI's powerful APIs makes these tasks seamless and accessible through a FastAPI web application.

## Features

### Meal Plan Generation

- **Endpoint:** `/meals_plan`
- **Description:** Takes user-specified ingredients and caloric preferences, generates three meals with titles and recipes, and returns the meal plan.

### Image Generation for Meals

- **Endpoint:** `/generate_images`
- **Description:** Utilizes the OpenAI DALL-E API to create images for each meal based on the generated titles. The images are then packaged into a downloadable zip file.

### YouTube Audio Summarizer

This project includes scripts to download audio from YouTube videos and generate a summary using OpenAI's APIs.

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/Ammar-Abdelhady-ai/Openai-api.git
cd Openai-api
