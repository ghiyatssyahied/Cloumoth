# Cloumoth Music Player

## Description
Cloumoth Music Player is an Android-based music player application that allows users to play audio files stored on their device. This application features a modern user interface with audio visualization and intuitive playback controls, providing an enhanced music listening experience.

## Features
- Support for multiple audio formats (MP3, WAV, AAC)
- Elegant user interface with gradient background
- Audio visualization that responds to music playback
- Comprehensive playback controls:
  - Play/Pause
  - Next/Previous track
  - Fast forward/rewind (10 seconds)
  - Seekbar for precise navigation
- Background playback capability
- Automatic listing of all audio files on device
- Animated circular music icon

## Screenshots
*[Screenshots would be placed here]*

## Technologies Used
- Android Studio
- Kotlin programming language
- XML for layouts
- MediaPlayer API for audio playback

## Libraries
- [Dexter](https://github.com/Karumi/Dexter) - For runtime permissions management
- [Audio Visualizer Android](https://github.com/gauravk95/audio-visualizer-android) - For audio visualization effects

## Setup and Installation
1. Clone this repository
2. Open the project in Android Studio
3. Build and run the application on your Android device or emulator
4. Grant the necessary permissions when prompted:
   - Storage permission (to access audio files)
   - Audio recording permission (for visualizer functionality)

## Usage
1. Launch the app
2. Grant required permissions
3. Browse and select a song from the list
4. Use the playback controls to control your music:
   - Center button: Play/Pause
   - Right button: Next track
   - Left button: Previous track
   - Far right button: Fast forward 10 seconds
   - Far left button: Rewind 10 seconds
   - Seekbar: Navigate through the song

## Project Structure
- `MainActivity.java` - Lists all available audio files on the device
- `PlayerActivity.java` - Handles music playback and controls
- `slashActivity.java` - Splash screen shown on app startup
- Layout files for the user interface
- Drawable resources for buttons and background

## Requirements
- Android 5.0 (API 21) or higher
- Storage permission
- Audio recording permission (for visualizer)
