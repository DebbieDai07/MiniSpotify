# MiniSpotify: A Kotlin-based Music Android App

An Android music application inspired by Spotify, designed to deliver a seamless music playback experience. This app utilizes MVVM architecture, local caching, and global playback capabilities.


## Tech Stack

#### Front-End:
- **Jetpack Compose**: For creating a responsive and modern user interface with MVVM architecture.
- **Jetpack Navigation**: For managing seamless app navigation through BottomBar and other components.

#### Back-End:
- **json-server**: For mocking RESTful API endpoints to simulate backend functionality.
- **Retrofit**: For managing network requests and API integration.

#### Data Management:
- **Room Database**: For implementing local caching, enabling offline access to favorite features.

#### Playback:
- **Google ExoPlayer**: For handling global music playback functionality.


## Project Structure
#### spotify_app/: 
Contains the Android app built with Kotlin using Jetpack Compose and other Jetpack libraries.
#### spotify_backend/: 
Backend mock server setup using json-server to simulate RESTful APIs.


## Running Setup
- Start the backend server as described above.
- Launch the Android app from Android Studio.
- Ensure the backend server is reachable from the app (adjust URLs in the app if needed to match your local setup).


**More setup details crecorded in README of spotify_app/ and spotify_backend/ seperately.**