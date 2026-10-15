# ArithmoAI — AI-Based Differentiated Mathematics Learning

## About the Project

ArithmoAI is a web-based educational application that helps students practise mathematics at their own pace. It uses AI to generate mathematics exercises with different difficulty levels.

## Main Features

- **AI Task Generation:** Creates new mathematics exercises using the Gemini API.
- **Three Difficulty Levels:** Foundation, Standard, and Advanced.
- **Two Mathematics Topics:** Arithmetic Progression and Area of a Triangle.
- **Hints and Solutions:** Provides hints and step-by-step explanations.
- **Answer Checking:** Checks students' answers and gives feedback.
- **Fallback Mode:** Generates rule-based tasks when the AI service is temporarily unavailable.

## Technologies Used

- HTML — website structure
- CSS — website design and layout
- JavaScript — interactive features and task generation
- Google Gemini API — AI-generated exercises
- Cloudflare Workers — secure backend API

## How to Use

1. Open the ArithmoAI website.
2. Choose a mathematics topic.
3. Select a difficulty level.
4. Generate a new task.
5. Enter your answer and click **Check Answer**.
6. Use **Show Hint** or **Show Solution** if needed.

## Project Goal

The goal of ArithmoAI is to support differentiated learning by providing mathematics practice at different difficulty levels and helping students learn independently.

## Security

The Gemini API key is stored as a secret in Cloudflare Workers and is not included in the public website code.
