# Emotion-Based Music Recommendation Web App

This project, **EmotionMusicApp**, is a Flask-based web application that detects emotions using a webcam feed and plays mood-based Spotify playlists.

## Features
- Real-time emotion detection using a trained ResNet50 model.
- Displays webcam feed with detected emotions overlaid.
- Automatically plays Spotify playlists based on the detected emotion.

## Project Structure
   ```bash
    EmotionMusicApp/
    ├── app.py                  # Main application script
    ├── Models/
    │   └── RestNet50_OAHEGA_1_without_Ahe.keras   # Trained emotion detection model
    ├── templates/
    │   └── index.html          # HTML template
    ├── static/
    │   └── whiteguitar.jpg     # Background image
    ├── .env                    # Spotify API credentials (not included for security)
    ├── requirements.txt        # Python dependencies
    └── README.md               # Project documentation

```
## Setup Instructions
- ### Note:
❗ **Important:** Dear **Dr. Omar** This project already includes valid Spotify Developer credentials in the `.env` file. You do not need to create your own credentials.

### 1. Prerequisites
- Python 3.8 or higher
- A working webcam
- A Spotify Developer account ([Create one here](https://developer.spotify.com/))



### 2. Install Dependencies
1. Clone the repository or unzip the project files.
2. Navigate to the project directory in a terminal:
   ```bash
   cd EmotionMusicApp
### 3. Create and activate a virtual environment:
- On Windows:
     ```bash
    python -m venv venv
    venv\Scripts\activate
    ```
- On macOS/Linux:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```
### 4. Install required libraries:
```bash
     pip install -r requirements.txt
   ```  
### 5. Configure Spotify Credentials
- ### Note:
❗ **Important:** Dear **Dr. Omar** This project already includes valid Spotify Developer credentials in the `.env` file. You do not need to create your own credentials.
Proceed to step 6 with the setup instructions, and the app will connect to Spotify automatically using the provided credentials.

1. Create a .env file in the project root with the following content:
   ```bash
   SPOTIFY_CLIENT_ID=your_actual_client_id
   SPOTIFY_CLIENT_SECRET=your_actual_client_secret
2. Replace your_actual_client_id and your_actual_client_secret with your Spotify Developer credentials.
### 6. Run the App
1. Start the Flask app:
    ```bash
    python app.py
2. Access the app in a browser at http://localhost:5000.
## Usage
1. Emotion Detection:
   - Ensure your webcam is connected.
   - Access the app to view the live webcam feed with detected emotions.
2.  Spotify Integration:
      - Click the Spotify AutoPlay button.
      - Log in to your Spotify account if prompted.
      - Music will play based on the detected emotion.
## Known Issues
- Ensure Spotify is running on an active device for music playback.
- Emotions may take a few seconds to detect and switch music.
## Testing Instructions
1. Test different facial expressions to trigger mood-based playlists.
2. Verify Spotify playback on connected devices.
3. Ensure all features work smoothly as per the setup.
## Authors
- This project was developed by:
1. Alaa Asfour
2. Jason Quantrill
3. Million Solomon
4. Murrium Zaheer
5. Xioadon Bi