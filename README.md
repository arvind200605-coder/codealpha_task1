# Flashcard Quiz Web Application

A responsive, interactive flashcard application designed to help students improve learning and memory through quizzes, spaced repetition, and progress tracking. Developed as part of a CodeAlpha internship task.

## Live Demo

**[Launch Flashcard Quiz](https://arvind200605-coder.github.io/codealpha_task1/)**

## Features

- **Flashcard Management:** Create, edit, and delete flashcards and study decks.
- **Multiple Study Modes:** Classic, Quick Quiz, Speed Mode, Review Mode, and Review Mistakes.
- **Spaced Repetition:** Uses a Leitner-box approach to prioritize cards and schedule future reviews.
- **Progress Tracking:** Track reviewed cards, accuracy, mastered cards, and study history.
- **Gamification:** Earn experience points (XP), level up, maintain study streaks, and unlock achievements.
- **Daily Challenge:** Aim to review 10 flashcards per day.
- **Theme Customization:** Choose light, dark, or system appearance.
- **Search and Filters:** Find decks and cards and filter cards by learning status.
- **Responsive Interface:** Supports desktop and mobile screen sizes.
- **Local Data Persistence:** Stores flashcards, decks, settings, and progress in browser local storage.

## Technologies Used

- **HTML5** — application structure
- **CSS3** — styling, responsive layout, animations, and themes
- **JavaScript** — application logic, study modes, progress tracking, and interactions
- **Browser localStorage** — saving user data locally

## Getting Started

### Run Locally

1. Clone or download this repository.
2. Open `index.html` in a modern web browser.
3. Create a deck or use the starter deck.
4. Add flashcards and choose a study mode.

### Clone the Repository

```bash
git clone https://github.com/arvind200605-coder/codealpha_task1.git
cd codealpha_task1
```

Open `index.html` in your browser. No backend server or package installation is required.

## How It Works

1. Create a deck and add questions with their answers.
2. Select a study mode and review the flashcards.
3. Mark each card as known or needing review.
4. Track learning progress, accuracy, XP, and achievements.
5. Return to cards when they become due for review.

The application uses a Leitner-box system to increase review intervals for cards marked as known and return cards needing review to the first box.

## Data Storage

The application saves data in the browser's local storage. Data is not automatically synchronized across devices or browsers. Clearing browser storage may remove saved application data.

## Project Objective

The objective of this project is to demonstrate front-end web development, interactive user interface design, JavaScript-based state management, browser storage, and basic spaced-repetition learning techniques.

## Author

Developed for the **CodeAlpha Internship Program**.

## Repository

[View source code on GitHub](https://github.com/arvind200605-coder/codealpha_task1)
