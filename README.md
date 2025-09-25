##AI Mood-Based Playlist Generator
---

An intuitive web application that generates personalized Spotify playlists based on natural language mood descriptions. Powered by Gemini AI for mood interpretation and Spotify API for playlist creation, this project makes music discovery effortless and fun.

##Overview
---
Finding the right playlist for your mood often takes time and effort. This application solves that problem by allowing users to type in a mood, vibe, or activity (e.g., "chill evening by the beach", "focus and study", "dance party with friends").
Gemini AI interprets the natural language input.
Spotify API curates a playlist that matches the vibe.
The app then displays the playlist with track details, album art, and playback options.

##Features
---
- Natural language mood input processing with Gemini AI
- Real-time playlist generation using Spotify API
- Responsive UI built with React.js, optimized for desktop and mobile
- Display of generated playlists with track titles, artists, album art, and Spotify links
- Basic playback controls linking to Spotify app
- Backend API built with Node.js and Express for AI processing and Spotify integration
- Environment-based configuration for API keys and deployment

## Technology Stack
---

- Frontend: React.js, HTML5, CSS3
- Backend: Node.js, Express.js, Axios
- AI Integration: Gemini AI API
- Music Data: Spotify Web API
- Dev Tools: npm, nodemon, dotenv

## Installation

### Backend

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
### Frontend

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
## Usage
1. Open your browser and go to `http://localhost:3000`
2. Type your mood or vibe in the input box
3. Click "Generate Playlist" button
4. Explore your AI-generated, mood-based music playlist
---
📸 Screenshots ;-)
<img width="1901" height="1074" alt="Screenshot 2025-09-25 144649" src="https://github.com/user-attachments/assets/7056f822-3dd0-429c-9275-ff4398db2cc3" />
<img width="1916" height="1078" alt="Screenshot 2025-09-25 145006" src="https://github.com/user-attachments/assets/527487f3-f93b-45c4-a57a-55fa231e3c2b" />
<img width="1919" height="1076" alt="Screenshot 2025-09-25 153009" src="https://github.com/user-attachments/assets/d94e115a-19e4-4634-b898-dd6684fde93a" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 231436" src="https://github.com/user-attachments/assets/8544a54c-2a33-4f0d-a6a2-95aa9784dd97" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 230629" src="https://github.com/user-attachments/assets/f32f796f-0e80-4b42-bae2-14e572c4665a" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 230333" src="https://github.com/user-attachments/assets/71afcf1b-3c0d-421b-b6cb-12d9976b54f2" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 230002" src="https://github.com/user-attachments/assets/54082206-b645-4c85-b657-41f8d1b1c729" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 224933" src="https://github.com/user-attachments/assets/69b10040-a903-4865-9136-9b5bae0b160d" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 224048" src="https://github.com/user-attachments/assets/743296f9-7231-43b2-ab11-2264aaaaad31" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 223818" src="https://github.com/user-attachments/assets/e7dc2892-e37b-4049-8688-d7c2128b2d65" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 223657" src="https://github.com/user-attachments/assets/c59b5a97-8e40-402e-a1a1-cae62dc61451" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 221647" src="https://github.com/user-attachments/assets/f12a0aa7-3c10-4e12-b531-fe827218caa9" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 221633" src="https://github.com/user-attachments/assets/74bb481a-1682-40d6-b302-cfb0cb754ebb" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 221613" src="https://github.com/user-attachments/assets/7b001811-3c8e-41e0-825e-49efc83f5ed7" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 215526" src="https://github.com/user-attachments/assets/c95cf904-22c8-4a60-8279-b4d5ed8908b1" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 215221" src="https://github.com/user-attachments/assets/416d8062-6229-4241-9d1d-2bafcea03e57" />
<img width="1920" height="1020" alt="Screenshot 2025-09-24 215024" src="https://github.com/user-attachments/assets/009a70dc-b3d1-4f5b-ad23-fd829bef30f9" />
<img width="1920" height="1080" alt="Screenshot 2025-09-24 214426" src="https://github.com/user-attachments/assets/95bbc224-15f5-4c5e-94c6-0bb65bae0f70" />
<img width="1913" height="990" alt="Screenshot 2025-09-24 214355" src="https://github.com/user-attachments/assets/ad7888ae-8727-4c44-8c59-323c0179ada1" />
