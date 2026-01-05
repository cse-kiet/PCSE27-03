
CodeZoo: A Gamified Platform for Computer Science Education

CodeZoo is an intelligent, gamified web application designed to revolutionize how beginners learn computer science concepts. Inspired by the success of language-learning platforms like Duolingo, CodeZoo transforms complex topics—such as loops, variables, and data structures—into bite-sized, interactive lessons.

By integrating Generative AI, gamification mechanics, and practical coding environments, the platform bridges the gap between passive learning and hands-on application.

🚀 Key Features

Gamified Learning Path: Users earn Experience Points (XP), maintain daily streaks, unlock badges, and compete on global leaderboards to stay motivated.


AI-Powered Virtual Tutor: Leveraging the Google Gemini API, the system provides real-time, personalized explanations whenever a user answers a question incorrectly.


Visual Coding Lab: A drag-and-drop interface designed to teach algorithmic logic without the frustration of syntax errors.


Practice Lab (Python): An in-browser compiler powered by Skulpt, allowing users to write and execute Python code instantly without any local setup.


Progress Tracking: A sophisticated backend tracks user consistency through "Streaks" and "Levels," visualized via a "Skill Tree" dashboard.

🛠️ Tech Stack
Frontend

React 19 (Vite): For a dynamic and responsive user interface.


Tailwind CSS: Modern styling with support for Dark Mode.


Skulpt: For client-side Python compilation.

Backend

Node.js & Express.js: Robust server-side logic and RESTful API development.


MySQL: Reliable relational database for storing user progress, courses, and skills.

AI Integration

Google Gemini API (Gemini 2.5 Flash): Generates human-like feedback and beginner-friendly explanations.

🏗️ System Architecture
CodeZoo follows the MERN Stack principles (utilizing MySQL for relational data persistence).


Client-Side: Handles interactive lessons, visual coding blocks, and local code execution.


Server-Side: Manages authentication, progress synchronization, and gamification logic.


AI Service: Constructs prompts based on user mistakes to fetch concise, contextual feedback.
