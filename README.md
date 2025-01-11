# Spotify-shuffle-generator
# Spotify Shuffle Generator

A Python-based Spotify Shuffle Generator that allows users to generate a shuffled playlist from their saved tracks using the `Spotipy` library in Python. With this tool, you can enjoy your Spotify library in a random and fun way.

## Features

- **Shuffle Your Saved Tracks**: Randomly shuffle tracks from your saved Spotify library.
- **Simple Setup**: Easy-to-follow steps to authenticate and use the tool.
- **Customizable**: Modify the number of shuffled tracks or how the output is formatted to your needs.

## Installation

### Prerequisites

- Python 3.x
- Spotify account
- Google Colab or Jupyter Notebook
- `Spotipy` library to interact with the Spotify API

### Steps to Install and Run

1. **Install the Spotipy library** in Google Colab or Jupyter Notebook by running:

   ```python
   !pip install spotipy
Set up Spotify Developer Application:

Go to the Spotify Developer Dashboard and create an application to get your client_id, client_secret, and redirect_uri.
Make sure to set your redirect_uri to "http://localhost:8888/callback" in the Spotify Developer Dashboard.
Replace the credentials in the code with your client_id and client_secret.

Run the script to generate a shuffled playlist:

python
Copy code
generate_shuffle_playlist()
Authentication: The first time you run the script, you will be prompted to authenticate via Spotify. Follow the steps to authorize and paste the authorization code when prompted.

How to Use
Once the authentication is done:

The script fetches all your saved tracks from Spotify.
It then shuffles the list of tracks and displays the top 20 shuffled tracks with the track name and artist.
You can adjust the number of tracks or modify the script according to your preferences.
Example Output:
text
Copy code
Your shuffled playlist:
1. Song A by Artist 1
2. Song B by Artist 2
3. Song C by Artist 3
...
20. Song T by Artist 20
Project Structure
bash
Copy code
spotify-shuffle-generator/
├── spotify_shuffle_generator_colab.ipynb   # Colab notebook for generating shuffled playlist
└── README.md                               # Project documentation
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Thanks to Spotify for providing the API to access user libraries.
Special thanks to the Spotipy library for making it easy to interact with the Spotify Web API.
Author
This project is maintained by Rohithds.

Troubleshooting
Authentication issues: Ensure that your client_id, client_secret, and redirect_uri are correctly configured in the Spotify Developer Dashboard and the code.
Missing tracks: Make sure that you have saved some tracks in your Spotify library. If no tracks are fetched, try re-authenticating or check your library.
vbnet

