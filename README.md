# Habit Tracker

A full-stack habit tracker application built with Flask and MongoDB that helps users track their daily habits and mark their completion. The app allows users to add new habits, view habits by date, and record habit completions in a user-friendly interface.

## Features

- **Add Habits**: Easily add new daily habits.
- **View Habits**: Display habits for the current date or a selected date.
- **Complete Habits**: Mark habits as complete for a specific day.
- **Dynamic Date Range**: View habits within a 7-day range (3 days before and after the selected date).
- **Data Persistence**: All habits and completions are stored in a MongoDB database.

## Tech Stack

- **Backend**: Flask (Python)
- **Database**: MongoDB
- **Environment Variables**: dotenv

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/habit-tracker.git
    cd habit-tracker
    ```

2. Create a virtual environment and activate it:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # For Windows: venv\\Scripts\\activate
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up environment variables:
    Create a `.env` file in the project root and add your MongoDB connection string:
    ```env
    MONGODB_URI=your_mongodb_connection_string
    ```

5. Run the app:
    ```bash
    flask run
    ```

6. Access the application in your browser at `http://127.0.0.1:5000`.

## Usage

- **Homepage**: View the list of habits and their completion status for a given day.
- **Add Habit**: Navigate to `/add` to add a new habit.
- **Mark Habit as Complete**: Complete habits directly from the homepage by selecting the checkmark button.

