# pitchPerfect

Pitch Perfect project for Udacity iOS Nanodegree

The Pitch Perfect app for  **Intro to iOS App Development with Swift** lesson of **Udacity's iOS Developer Nanodegree** course.

The app allows users to record a sound using the device’s microphone. It then allows the user to play the recorded sound back with 
different sound modulations: Slow, Fast, Chipmunk, Darth Vader, Echo and Reverb effect.

## Implementation

The app has two view controllers:

- **RecordSoundsViewController** - consists a record button with a microphone image. Tapping this microphone button 
starts an audio recording session. This View Controller also has a stop button. When the stop button is clicked, the app completes recording and then show the PlaySound controller.

- **PlaySoundsViewController** - contains six buttons to play the recorded sound file with different effects and a button to stop the playback.

The application uses code from `AVFoundation` to record sounds from the microphone (`AVAudioRecorder`) and play recorded audio with effects (`AVAudioPlayer`, `AVAudioEngine`).

## Requirements

 - Xcode 8
 - Swift 3.0
 
 
