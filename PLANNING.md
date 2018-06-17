# Project Planning
## Problem Statement
### Primary User
Me (A spotify user who wants to track new songs released by my favorite artist)
### User Needs Statement
As a spotify user who listen to music everyday. I need an application to show new song released by my favorite artists, add to own 
playlist and have access to the trending album, artists and songs.

### As-is Process Description
  + Request mega data for the artist.
  + Obtain a list of song for the artist.
  + Request input for songs that user wants to add to the playlist.

### To-be Process Description
  + Obtain a list of songs user wants to add to the playlist.
  + Run a script to add songs to add the playlist.

## Information Requirements

### Information Inputs

A `artist_song.csv` file containing a list of particular artist's song and detail.

### Information Outputs

A `playlist.csv` file contining a list of songs with artist name, released date and song detail.

## Technology Requirements

### APIs and Web Service Requirements

I thought I might need to use the [SPOTIFY API](https://developer.spotify.com/dashboard/login) to download all files to endpoint for the use of my application.

### Python Package Requirements

The application does require third-party package called 'Node.js' and 'npm'
Other than that, I would also use package like `csv`, `json`,`os`,`pdb`, `request` and `datetime`.

### Hardware Requirements
The application will be running on my own local machine. I have no plans to deploy this application to a public server.
