# Quizzler: React Quiz Application

## Overview
Quizzler is an interactive React-based quiz application that tests users' knowledge with a dynamic, engaging interface. The app features a point system, progress tracking, and immediate feedback on answers.

## Features
- 🎯 Point-based scoring system
- 📊 Progress bar to track quiz advancement
- 🌈 Dynamic answer highlighting (correct/incorrect)
- 🚀 Smooth navigation with Next button
- 📱 Responsive design

## Technologies Used
- React
- React Hooks (useReducer, useEffect)
- JSON for question data management

## Project Structure
```
quizzler/
│
├── src/
│   ├── components/
│   │   ├── App.js          # Main application component
│   │   ├── Header.js       # App header
│   │   ├── Main.js         # Main content wrapper
│   │   ├── Progress.js     # Quiz progress bar
│   │   ├── Question.js     # Individual question component
│   │   ├── Options.js      # Answer options component
│   │   ├── NextButton.js   # Navigation button
│   │   └── ...
│   │
│   ├── index.js
│   └── index.css
│
└── data/
    └── questions.json      # Quiz questions database
```

## How It Works
1. The app loads questions from a JSON file
2. Users start the quiz and answer questions
3. Points are awarded for correct answers
4. Progress is tracked visually
5. Users can navigate through questions

## Getting Started

### Prerequisites
- Node.js
- npm or yarn

### Installation
1. Clone the repository
2. Install dependencies
   ```bash
   npm install
   ```
3. Start the development server
   ```bash
   npm start
   ```

## Quiz Mechanics
- Each question has a point value
- Correct answers increase the total points
- A progress bar shows quiz completion
- Next button allows moving to subsequent questions

## Future Improvements
- Add more question categories
- Implement difficulty levels
- Create a leaderboard
- Add timer functionality