Emotional Music Generator

Project Overview

This is an Adaptive Music Therapy Generator prototype developed for the 52685 Working with Data and Code assessment . The project uses Python in TunePad to create dynamic, mood-based music compositions inspired by music therapy principles (e.g., slow tempos for 'down' moods to calm , intense rhythms for 'angry' to release tension ). It maps moods ('happy', 'energetic', 'down', 'angry') to algorithmic adjustments in tempo, scales, chords, volume, and drum patterns, with randomness for replayability and therapeutic variety.





Key features:

Mood parameterization: Adjusts scales (major/minor), volume, intensity, and tempo based on emotion .

Layered composition: Drums, melody, and harmony via loops, conditionals, and random variations .

Original code focus: Custom functions (set_mood_params) and logic (i % 4)  for emotional mapping.

Requirements
Environment: TunePad (browser-based Python music editor), no installation needed. Access at tunepad.com.

Dependencies: Built-in TunePad libraries (tunepad.constants, tunepad.chords) and Python's random module. No external installs required.

Hardware: Computer with browser and audio output.

File Structure
This repository contains four JSON files exported from TunePad. Each file holds the complete Python code for a specific mood, including multiple instrument layers within that file .


emotional_music_angry.json 




emotional_music_energetic.json 


emotional_music_happy.json 


emotional_music_down.json 




No additional assets (e.g., audio files) are required; all sounds are generated via TunePad's built-in instruments.

How to Run the Prototype
To ensure that you can fully view the project files, including all the annotations and comments I made in the code, please follow these steps to import the project :


Download Files: Download the original .json file for the desired mood mode from this GitHub repository (e.g., emotional_music_angry.json) .



Access TunePad: Log into the tunepad.com website.


Import Project: Use the Import function on the TunePad interface to upload the downloaded .json file to the website .


Critical Setup: Manually set the BPM and instrument on the TunePad interface according to the print output at the top of the code . This is essential for achieving the intended emotional effect.

Run: Click the play button.

Acknowledgments
TunePad documentation and tutorials (learn.tunepad.com) for basic functions like playNote() and constants .



Inspired by: Horn et al. (2022) Introduction to Digital Music with Python; De Witte et al. (2020) on music therapy effects.

All original code (e.g., mood functions, random logic) by Zhijie Tao (Edison).

License
This project is for educational purposes. Feel free to modify, but cite if reusing.

For issues, contact: Zhijie.tao@student.uts.edu.au






