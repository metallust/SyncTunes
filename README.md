# YouTube to Spotify Playlist Converter

A Python application that converts YouTube playlists to Spotify playlists.

## Description

This application allows you to convert your favorite YouTube playlists into Spotify playlists. It utilizes the pytube to access unlisted or public playlist and Spotify Web API to fetch the YouTube playlist details and create a corresponding playlist on Spotify.

## Features

- Convert YouTube playlists to Spotify playlists
- Mapping of YouTube videos to Spotify tracks based on title and artist information

## Setup

To set up the YouTube to Spotify Playlist Converter, follow the steps below:

### 1. Prerequisites

- Python 3.7 or above installed on your machine
- `pip` package manager

### 2. Clone the Repository

    $ git clone https://github.com/your-username/youtube-to-spotify-playlist-converter.git
    $ cd youtube-to-spotify-playlist-converter

### 3. Install Dependencies

    $ pip install -r requirements.txt

### 4. Obtain API Credentials

In order to use the application, you need to obtain API credentials for Spotify Web API.

#### Spotify Web API

1. Go to the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/).
2. Create a new application (if you haven't already).
3. Note down the **Client ID** and **Client Secret**.
4. Add a redirect uri `http://127.0.0.1:8080/`

### 5. Configuration

- Rename the `sample_config.py` file to `config.py`.
- Replace `"YOUR_CLIENT_ID"` and `"YOUR_CLIENT_SECRET"` in `config.py` with the respective values obtained from the API credentials.

### 6. Run the Application
    $ python app.py


The application will start running. Follow the prompts to provide the YouTube playlist URL and authorize the Spotify account to create the playlist.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please feel free to open a pull request.



