# App notes

## Modules

- music player backend service
- cli interface with music player controls
- consume the backend service on the cli application using ssh

## Things to note

- is there a way to play sound in the cli? Yes, we will use mpg123 (a cli package)
- or is there a way to connect the cli to the system's speaker hardware? Yes. mpg123 does that
- ways to make it work seamlessly

## TODO

- save the audio files in a file server like cloudinary then the backend service gets the audio from there

## User story

- the frontend makes an ssh request to the backend service
- the backend service receives the ssh request from the frontend and responds with links to the audio files
- the frontend receives the response and displays on the cli
- the frontend makes a request to play a selected audio using the mpg123
- the frontend can pause or stop the audio
- the frontend can play next or prev audio
