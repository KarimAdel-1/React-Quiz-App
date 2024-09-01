# React Quiz App

Welcome to the **React Quiz App** repository! React Quiz App is an interactive and engaging quiz application built with React. This app showcases advanced React features such as state management with the Context API, custom hooks, and responsive design principles. It offers dynamic quizzes with a countdown timer, custom animations, and a user-friendly interface optimized for all devices. With a JSON server simulating an API, this project provides a realistic environment for testing and learning React concepts.


## 🌟 Features

- **Dynamic Quizzes:** The app dynamically loads quiz questions and tracks the user's progress.
- **State Management:** The application uses the Context API to manage the quiz state, making the app scalable and maintainable.
- **Timed Quizzes:** A countdown timer adds an element of challenge to each quiz session.
- **Responsive Design:** The application is fully responsive, providing an optimal user experience across devices.
- **Custom Animations:** Smooth and engaging transitions enhance the overall user experience.

## 🚀 Getting Started

### Prerequisites

- **Node.js** and **npm**: Make sure you have Node.js installed on your machine. You can download it [here](https://nodejs.org/).

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/KarimAdel-1/react-quiz-app.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd react-quiz-app
   ```
3. **Install the dependencies:**
   ```bash
   npm install
   ```

### Running the Application

1. **Start the development server:**
   ```bash
   npm start
   ```
2. Open your browser and visit `http://localhost:3000` to view the application.

### Running the JSON Server

The app uses a JSON server to simulate an API for fetching quiz questions. To start the JSON server:

```bash
npm run server
```

This will start the server on `http://localhost:8000`.

## 📚 Usage

1. Upon launching the app, you'll be greeted with a welcome screen.
2. Click "Let's start" to begin the quiz.
3. Answer the questions as they appear. Your progress and score will be tracked in real-time.
4. Upon completing the quiz, you can view your score and restart the quiz if desired.

## 🛠️ Technologies Used

- **React:** Core library for building the user interface.
- **Context API:** Manages global state for the quiz.
- **JSON Server:** Mocks a backend to serve quiz questions.
- **CSS:** Custom styles for the application.

## 🎨 Styling

The application is styled with custom CSS to ensure a clean and user-friendly interface. The layout is designed to be responsive and works well on various screen sizes.

## 💻 Code Overview

- **App Component:** The main component that renders the different screens based on the quiz status.
- **Header Component:** Displays the app's title and logo.
- **Question Component:** Shows the current question and options for the user to select.
- **Timer Component:** Displays a countdown timer for the quiz.
- **FinishScreen Component:** Displays the user's final score and an option to restart the quiz.
