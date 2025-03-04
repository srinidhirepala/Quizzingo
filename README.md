# Kivy Quiz App

## Overview

The Kivy Quiz App is a Python-based application built using the **Kivy framework**. It allows users to answer a series of multiple-choice questions, track their score, and provides real-time feedback. Once the quiz is completed, the user will see a congratulatory message and an image based on their score.

## Features

- **Multiple Choice Questions**: The app presents 5 multiple-choice questions.
- **Real-Time Feedback**: Buttons change color (green for correct answers, red for incorrect answers).
- **Score Calculation**: The user's score is updated after each question.
- **End of Quiz Screen**: Displays the total score and a congratulatory image based on performance.

## Technologies Used

- **Python**: Programming language used for app development.
- **Kivy**: Framework used for building the graphical user interface (GUI).
- **Clock**: To manage delayed button color reset.
- **ScreenManager**: To handle different screens in the app.

## Installation

### Prerequisites

Before running the application, ensure that you have the following installed on your machine:

- Python 3.x or higher
- Kivy library (can be installed via pip)

### Steps

1. **Clone the Repository**:
   Clone the project repository to your local machine:

   ```bash
   git clone <repository_url>
2.**Navigate to the Project Directory: Change to the project directory**:

```bash
cd kivy-quiz-app
```

3.**Install Dependencies: Install the required dependencies, specifically the Kivy library**:

```bash
Copy
pip install kivy
```
4.**Run the Application: Start the application:**
```bash
python main.py
```
### Screenshots

**Sample Output**

After completing the quiz, the user will see one of the following screens:

Congratulations Screen: Displays a message with the user's score and an image if the score is above half of the total points.
Sad Emoji Screen: Displays a message with the user's score and a sad emoji image if the score is below half.

