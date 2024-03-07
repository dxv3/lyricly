**Basic Lyricly** 🎶

A simple music discovery tool that helps you find songs based on genre and artist using the Spotify API.

**Features**
*   🔎 Search Spotify's catalog of tracks by genre.
*   🎤 Optionally filter the search by artist name. 
*   🎵 Provides song titles, artist names, and direct Spotify links for easy listening.

**Prerequisites**
*   A Spotify account (a free account is fine)
*   A Spotify developer application set up (see instructions below)
*   Python 3 installed 
*   The `spotipy` library installed (`pip install spotipy`)

**Setup** ⚙️
1.  **Spotify Developer Account:**
    *   Go to the Spotify developer dashboard: [https://developer.spotify.com/](https://developer.spotify.com/)
    *   Create an application and obtain your Client ID and Client Secret.

2.  **Edit `basic_lyricly.py`:**
    *   Replace the placeholders `YOUR_CLIENT_ID` and `YOUR_CLIENT_SECRET` with your actual credentials.

**Usage** 🚀

1.  Run the script from your terminal:
    ```bash
    python basic_lyricly.py
    ```
2.  Follow the prompts:
    *   Enter your Spotify username.
    *   Enter the genre you want to search.
    *   *(Optional)* Enter an artist name to refine the search.

**Known Limitations** 🚧
*   Does not search lyrics directly (Spotify's API doesn't provide this).
*   Genre filtering may not be perfect, as it relies on Spotify's own genre classification.

**Future Enhancements** ✨
*   **Explore possible integration with external lyrics APIs for more targeted searches.**
*   Create a user-friendly web interface.
*   Add more advanced search options.

**Contributing** 🤝
This is a basic project with lots of room for expansion! Feel free to suggest features, contribute improvements, and fix any bugs you encounter. 

**Disclaimer** ⚠️
This project is for educational and experimental purposes. Please respect music copyright and Spotify's API terms of service. 
