# App notes

## Modules

- music player backend service
- cli interface with music player controls
- consume the backend service on the cli application using ssh

## Things to note

- is there a way to play sound in the cli? Yes
- or is there a way to connect the cli to the system's speaker hardware? Yes. we have to get one
- ways to make it work seamlessly

## TODO

- save the audio files in a file server like cloudinary then the backend service gets the audio from there

## User story

- the frontend makes an ssh request to the backend service
- the backend service receives the ssh request from the frontend and responds with links to the audio files
- the frontend receives the response and displays on the cli
- the frontend makes a request to play a selected audio
- the frontend can pause or stop the audio
- the frontend can play next or prev audio
