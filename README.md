# spotify-play
This is a simple web app that serves to manage playlists and queue tracks in a few ways that Spotify's current interface cannot. The intent of this project is mainly just to learn the basics of Node and to get a bit more comfortable developing web apps.

## Current features
- Basic media controls
- Add/remove songs to Now Playing queue
- Add/remove entire or partial playlists to Now Playing queue
- Reorder queued tracks

## Planned features
- Retain position and track of previous queues

## Config
A config.json file should be included in the project root including port (optional), client_id, and client_secret.

Example config.json:
```
{
    "port": 8888,
    "client_id": "id_here
    "client_secret": "secret_here"
}
