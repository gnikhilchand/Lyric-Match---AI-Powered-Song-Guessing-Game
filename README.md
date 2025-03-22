# Lyric-Match---AI-Powered-Song-Guessing-Game 🎵

**Lyric Match** is a fun and interactive web application that challenges users to guess the title of an English song based on a short snippet of its lyrics. The app uses AI to generate lyric snippets and provides a leaderboard to track high scores.

---

## Features

- **Guess the Song:** Users can guess the song title based on a short lyric snippet.
- **Score Tracking:** Tracks the user's score for correct guesses.
- **Leaderboard:** Displays the top 10 scores.
- **AI-Powered:** Uses an AI model to generate lyric snippets.
- **User-Friendly Interface:** Clean and intuitive UI for a seamless experience.
- **Model Used:** DeepSeek-r1

---

## Technologies Used

- **Frontend:** React.js
- **Backend:** FastAPI (Python)
- **Database:** SQLite (via SQLAlchemy)
- **AI Integration:** OpenRouter.ai (DeepSeek model)
- **Styling:** CSS

---

## Setup Instructions

### Prerequisites

- **Node.js** (for the frontend)
- **Python 3.8+** (for the backend)
- **npm** (Node Package Manager)

### Step 1: Clone the Repository

```bash
git clone (https://github.com/gnikhilchand/Lyric-Match---AI-Powered-Song-Guessing-Game.git)
```

### Step 2: Set Up the Backend

Navigate to the backend directory:

```bash
cd lyric-match-backend
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment:

On Windows:

```bash
venv\Scripts\activate
```

On macOS/Linux:

```bash
source venv/bin/activate
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

Start the FastAPI backend:

```bash
uvicorn main:app --reload
```

The backend will run at [http://127.0.0.1:8000](http://127.0.0.1:8000).

### Step 3: Set Up the Frontend

Navigate to the frontend directory:

```bash
cd ../lyric-match-frontend
```

Install the required npm packages:

```bash
npm install
```

Start the React app:

```bash
npm start
```

The frontend will run at [http://localhost:3000](http://localhost:3000).

---

## How to Play

1. **Enter Your Username:**
   - Enter a username to track your score.
2. **Generate a Lyric Snippet:**
   - Click the "Generate Lyric Snippet" button to get a short snippet of lyrics.
3. **Guess the Song:**
   - Enter your guess for the song title in the input field and click "Check Answer".
4. **See the Result:**
   - If your guess is correct, your score increases.
   - If your guess is incorrect, the correct song title is displayed, and the page reloads after 2 seconds.
5. **View the Leaderboard:**
   - Click the "Show Leaderboard" button to see the top  scores.

---

## API Endpoints

### Backend (FastAPI)

#### `POST /generate-lyric`
Generates a lyric snippet and returns it along with the correct song title.

#### `POST /check-answer`
Checks if the user's guess matches the correct song title and updates the score.

#### `GET /leaderboard`
Returns the top  scores from the leaderboard.

---

## Screenshots

**Screenshot 1**
- Home Screen

**Screenshot 2**
- Leaderboard

---


## License

This project is licensed under the MIT License.

---

## Contact

For questions or feedback, please contact:

- **Nikhil Chand** - 21f1003825@ds.study.iitm.ac.in

- **GitHub:** [gnikhilchand](https://github.com/gnikhilchand)

