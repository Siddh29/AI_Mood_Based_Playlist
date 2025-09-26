

https://github.com/user-attachments/assets/7e0351c9-aa52-4cd4-ad74-15024f628888

AI Mood-Based Playlist Generator
---

An intuitive web application that generates personalized Spotify playlists based on natural language mood descriptions. Powered by Gemini AI for mood interpretation and Spotify API for playlist creation, this project makes music discovery effortless and fun.

---
# Run on Vercel:-
https://mood-playlist-generator-caxz06w25-jainsiddh2910-7925s-projects.vercel.app
# Run on Netlify:-
https://app.netlify.com/projects/rad-unicorn-4d963a/deploys/68d69da8d0125d5436be11af

### Run Locally
---
1. Clone the repo:
   git clone https://github.com/Siddh29/AI_Mood_Based_Playlist.git

2. Navigate to the project folder:
   cd AI_Mood_Based_Playlist

3. Install dependencies:
   npm install

4. Start the app:
   npm start

Overview
---
Finding the right playlist for your mood often takes time and effort. 

This application solves that problem by allowing users to type in a mood, vibe, or activity (e.g., "chill evening by the beach", "focus and study", "dance party with friends").

Gemini AI interprets the natural language input.

Spotify API curates a playlist that matches the vibe.

The app then displays the playlist with track details, album art, and playback options.


Features
---
- Natural language mood input processing with Gemini AI
- Real-time playlist generation using Spotify API
- Responsive UI built with React.js, optimized for desktop and mobile
- Display of generated playlists with track titles, artists, album art, and Spotify links
- Basic playback controls linking to Spotify app
- Backend API built with Node.js and Express for AI processing and Spotify integration
- Environment-based configuration for API keys and deployment

Technology Stack
---

- Frontend: React.js, HTML5, CSS3
- Backend: Node.js, Express.js, Axios
- AI Integration: Gemini AI API
- Music Data: Spotify Web API
- Dev Tools: npm, nodemon, dotenv

Installation

# Backend

1. Clone the repository  
2. Navigate to `backend` folder  
3. Create `.env` file with:
    ```
    GEMINI_API_KEY=your_gemini_api_key
    SPOTIFY_CLIENT_ID=your_spotify_client_id
    SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
    ```
4. Install dependencies:
    ```
    npm install
    ```
5. Start backend server:
    ```
    npx nodemon server.js
    ```
# Frontend

1. Navigate to `frontend` folder  
2. Install dependencies:
    ```
    npm install
    ```
3. Start React app:
    ```
    npm start
    ```
---
# Usage
1. Open your browser and go to `http://localhost:3000`
2. Type your mood or vibe in the input box
3. Click "Generate Playlist" button
4. Explore your AI-generated, mood-based music playlist

Screenrecording of working model:-
---
https://github.com/user-attachments/assets/1031bfad-6058-4616-be1b-63f28843fa86
📸 Screenshots ;-)
#Live Working proof:-
<img width="1920" height="1080" alt="Screenshot 2025-09-26 164241" src="https://github.com/user-attachments/assets/2941b286-fdea-4fc7-b375-b7fe82999907" />
<img width="1920" height="1080" alt="Screenshot 2025-09-26 164219" src="https://github.com/user-attachments/assets/8c5ba419-b3c8-4990-9dda-cd0e64cb6e5c" />
<img width="1920" height="1080" alt="Screenshot 2025-09-26 164205" src="https://github.com/user-attachments/assets/aa9317ff-61a3-4340-bd5a-9ab9721c35c9" />

#Spotify connection proof:
<img width="1901" height="1074" alt="Screenshot 2025-09-25 144649" src="https://github.com/user-attachments/assets/7056f822-3dd0-429c-9275-ff4398db2cc3" />
<img width="1916" height="1078" alt="Screenshot 2025-09-25 145006" src="https://github.com/user-attachments/assets/527487f3-f93b-45c4-a57a-55fa231e3c2b" />
<img width="1919" height="1076" alt="Screenshot 2025-09-25 153009" src="https://github.com/user-attachments/assets/d94e115a-19e4-4634-b898-dd6684fde93a" />

#Backend process done proof:
<img width="1920" height="1020" alt="Screenshot 2025-09-24 231436" src="https://github.com/user-attachments/assets/8544a54c-2a33-4f0d-a6a2-95aa9784dd97" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 230002" src="https://github.com/user-attachments/assets/54082206-b645-4c85-b657-41f8d1b1c729" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 224933" src="https://github.com/user-attachments/assets/69b10040-a903-4865-9136-9b5bae0b160d" />

#gemini IAM & Admin access:
<img width="1920" height="1080" alt="Screenshot 2025-09-25 211408" src="https://github.com/user-attachments/assets/aab95b1b-5f39-4226-b4aa-1ffa22347de9" />
<img width="1400" height="856" alt="Screenshot 2025-09-25 211111" src="https://github.com/user-attachments/assets/46be12fc-6785-4f88-b861-292077c15945" />

#Gemini Connected by Google Cloud proof:
<img width="1920" height="1020" alt="Screenshot 2025-09-24 224048" src="https://github.com/user-attachments/assets/743296f9-7231-43b2-ab11-2264aaaaad31" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 223818" src="https://github.com/user-attachments/assets/e7dc2892-e37b-4049-8688-d7c2128b2d65" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 223657" src="https://github.com/user-attachments/assets/c59b5a97-8e40-402e-a1a1-cae62dc61451" />

#Rest initial installation proof:
<img width="1920" height="1020" alt="Screenshot 2025-09-24 215526" src="https://github.com/user-attachments/assets/c95cf904-22c8-4a60-8279-b4d5ed8908b1" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 215221" src="https://github.com/user-attachments/assets/416d8062-6229-4241-9d1d-2bafcea03e57" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 215024" src="https://github.com/user-attachments/assets/009a70dc-b3d1-4f5b-ad23-fd829bef30f9" />
<img width="1920" height="1080" alt="Screenshot 2025-09-24 214426" src="https://github.com/user-attachments/assets/95bbc224-15f5-4c5e-94c6-0bb65bae0f70" />
<img width="1913" height="990" alt="Screenshot 2025-09-24 214355" src="https://github.com/user-attachments/assets/ad7888ae-8727-4c44-8c59-323c0179ada1" />





