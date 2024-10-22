# GymGenius

**GymGenius** was developed during 2024 ShellHacks Hackathon at FIU. It is a full-stack AI-powered gym trainer that provides personalized gym advice and workout plans tailored to individual goals. The application allows users to create and export workout plans directly to Google Calendar in ICS format. GymGenius uses OpenAI's API to provide real-time gym suggestions based on user input, making it a smart companion for fitness enthusiasts.

## Features

- **AI-Powered Workout Advice**: Get personalized workout suggestions using OpenAI.
- **Workout Planner**: Create custom workout routines with specific exercises and sets/reps.
- **ICS Export**: Export workout schedules as ICS files compatible with Google Calendar.
- **User Profiles**: Track and store user data for customized experiences.

## Tech Stack

- **Backend**: Python, Flask, SQLAlchemy
- **Frontend**: HTML, CSS
- **AI**: OpenAI API for gym advice generation
- **Database**: SQLite (or any SQLAlchemy-supported database)
- **Deployment**: Flask server

## Getting Started

### Prerequisites

- **Python 3.x**: Ensure that you have Python installed on your machine.
- **OpenAI API Key**: You'll need an OpenAI API key to enable AI-powered features.
- **Flask**: Install Flask for running the application.

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/nfourari/GymGenius.git
   cd GymGenius
   ```

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**:
   Create a `.env` file in the root directory with the following content:
   ```bash
   OPENAI_API_KEY=your_openai_api_key
   ```

5. **Run the application**:
   ```bash
   python main.py
   ```

6. **Access the application**:
   Open your web browser and go to `http://127.0.0.1:5000`.

## Usage

- **Create a Profile**: Sign up or log in to start creating personalized workout plans.
- **Generate a Plan**: Use the AI assistant to create custom workout plans based on your goals (e.g., strength training, muscle building).
- **Export to Google Calendar**: Download the workout schedule as an ICS file and import it into Google Calendar to stay on track.

## Project Structure

- **static**: Contains static files (CSS, images, etc.)
- **templates**: HTML templates for the front end
- **app.py**: Main Flask application logic
- **models.py**: Database models for SQLAlchemy
- **routes.py**: Defines application routes
- **utils.py**: Helper functions
- **requirements.txt**: List of dependencies
- **Deployment**: Flask server

## AUTHORS: 
    **Adryel Gainza,
    Sebastian Menendez,
    Isaiah William,
    Noah Fourari**
