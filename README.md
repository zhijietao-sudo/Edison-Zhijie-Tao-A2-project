# Edison-（Zhijie-Tao）-A2-project

1. Title and Overview
Emotional Music Generator: An Adaptive Music Therapy Prototype
This project is an experimental adaptive music system built in the TunePad/Python environment, designed to generate customized music in real-time based on the user's input mood.

Developer: Edison

Development Environment: TunePad (Python)

2. Core Features and Parameters
The prototype translates abstract emotions into quantifiable musical parameters, facilitating the dynamic generation of four core mood modes:

Angry: Aims to release frustration and build tension. Tempo is fast (BPM 140) with maximum volume (127), and the melody includes extreme random leaps (random.randint(-24, 24)), emphasizing instability and conflict.

Energetic: Highlights vitality and playfulness. Uses a fast tempo (BPM 160) in the C Major scale, with random additions of woodblock or cowbell sounds (playNote(56)), creating a bright and dynamic rhythm.

Happy: Maintains a stable and uplifting mood. Medium tempo (BPM 120) with the bass drum on strong beats, and minimal rests (only when random.random() > 0.8), forming a smooth and cheerful rhythm.

Down / Sad: Focuses on calmness and softness. Slow tempo (BPM 60) with lower volume (90), sparse bass drum hits (i % 8 == 0), and long-sustained harmonies, evoking a reflective and tranquil atmosphere.

3. Code Structure and Running Instructions
File Structure
This repository contains four JSON files exported from TunePad, each holding the complete Python code for a specific mood:

  emotional_music_angry.json

  emotional_music_energetic.json

  emotional_music_happy.json

  emotional_music_down.json

Key Technical Points
Parameter Configuration: All mood parameters are defined within the set_mood_params(mood) function.

Instrument Layering: The code uses multiple channels (e.g., Channel 1 for melody and Channel 2 for harmony) played in parallel to create a more complex timbre.

Rhythmic Core: The loop uses the modulo operation (i % 4) to calculate the beat position, ensuring accurate placement of strong and weak beats.

How to Run the Prototype
To ensure that you can fully view the project files, including all the annotations and comments I made in the code, please follow these steps to import the project:

1）. Download Files: Download the original .json file for the desired mood mode from this GitHub repository (e.g., emotional_music_angry.json).

2）. Access TunePad: Log into the TunePad website.

3）. Import Project: Use the Import function on the TunePad interface to upload the downloaded .json file to the website.

4）. Critical Setup: Manually set the BPM and instrument on the TunePad interface according to the print output at the top of the code. This is essential for achieving the intended emotional effect.

5）. Run: Click the play button.







