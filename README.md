# My Spoty (Python)

Spotify API client application for users to search for artists, play tracks and show playlist details.

## Prerequisites

Create a [Spotify Client application](https://developer.spotify.com/dashboard/applications/), and note its Client Id and Client Secret, and store them in environment variables called `SPOTIPY_CLIENT_ID` and `SPOTIPY_CLIENT_SECRET`.

Install desktop [spotify client termnial](https://www.spotify.com/us/download/other/), direct to profile page after installation. When you're on your account and find your account shairng link, click `more` and then `share` and then `copy profile link`, the characters after /user will be the `user_id` (eg.xxxxxxxxxxxxxx).


(sample link:https://open.spotify.com/user/xxxxxxxxxxxxxx)


This repo uses the "dotenv" approach, but feel free to use whatever approach works for you.

## Installation

Install package dependencies:

```sh
pip install -r requirements.txt
# or
pip3 install -r requirements.txt
# or
pipenv install -r requirements.txt
```

If using Pipenv, the following commands assume you are running them from within a `pipenv shell`.

## Usage

Run the app:

```sh
python3 spotifyxxx.py user_id
