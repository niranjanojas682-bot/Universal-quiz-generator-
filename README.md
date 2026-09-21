OmniQuiz AI — Universal 4 Point Quiz & Exam Generator Tool
OmniQuiz AI is a distraction free silent quiz tool, which eliminates the need for pre-set trivia databases. Students can freely build and attempt their own customised quizzes with just four fields: Class/Standard, Book/Source, Subject/Topic, Target Exam/Purpose
It is powered from Google Gemini AI to produce relevant multiple choice questions featuring live countdown timers, visual only feedback, and detailed review analytics.
---
## 🎯 The 4 Point Generation Engine
The test taker customises their test session by entering the following:
1. Class / Standard: What academic level should the questions be generated for? (e.g: 10th, 12th, Undergrad, UPSC Aspirant etc)
2. Book / Source: The source material which the questions should be based on. (e.g: NCERT Physics, HC Verma, M. Laxmikanth, Dune)
3. Subject / Topic: What topic or chapter should the questions focus on? (e.g: Electrostatics, Revolt of 1857, Chapter 4)
4. Target Exam / Purpose: What exam is this practice test for? (e.g: CBSE Board, NEET, JEE Mains, Quick Revision)
---
## ✨ Features
- On demand AI question synthesis, directly powered from Google Gemini 2.5 Flash
- Offline / Demo mode: Smart generator that fakes questions, if no API key provided
- No background music or sound effects, as to remain non-distracting quiz environment
- Dynamic animated countdown timer, uses SVG ring that morphs from indigo to alert rose as time depletes
- Instant visual feedback for correct and wrong answers, in emerald and rose respectively
- Scorecard and question review analysis on completion
- Accuracy percentage and total time taken
- Question by question breakdown of your answers, correct answers and explanations
- Zero build tools required, runs as vanilla web app, playable in browsers
---
## 🛠️ Tech Stack

| Layer | Technologies Used |
| :--- | :--- |
| Structure | Semantic HTML5 |
| Styling | [Tailwind CSS](https://tailwindcss.com/) (CDN hosted) & CSS |
| Logic | Vanilla JavaScript (ES6+, Fetch API, Async/Await) |
| AI Engine | [Gemini API](https://ai.google.dev/) (`gemini-2.5-flash`) |
---

## 📂 Project Structure
```text
omniquiz/
├── index.html    # 4-point form, active quiz and scorecard
├── styles.css    # Transition animations, SVG timer ring and button styles
├── app.js      # Gemini API connection, timer and evaluation logic
└── README.md     # Documentation
```