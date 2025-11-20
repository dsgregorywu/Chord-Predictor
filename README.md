# Chord-Predictor


Project Title and Description
This is my tree-based chord predictor! It uses a Trie to store existing chord progressions from a Kaggle dataset, then searches that tree based on the inputted beginning chords from the user. This program is designed for beginner composers who don't yet have a great understanding of music theory in order to give ideas for chord progressions. This is something I struggle with as a musician and arranger, and would love for this project to be something that I can use in the future for my compositions.

Team Members and Roles:
Derec Gregory (Everything)

Installation & Setup
The only required package for this is csv, as it reads in the chord progressions from a csv file. 
To use my program, follow these steps:
Step 1: Run the program
Step 2: Enter your existing chord(s)
Step 3: Pick one that is recommended to you!

Usage Guide
See above! It's very user friendly and designed to be simple. If you don't give it a correct chord, it will ask you to try again so no worries for non-musicians! You input a chord or chord progression when asked, then you are outputted some amount of potential next chords, ordered from most frequent to least frequent. Higher up chords are found more commonly in chord progressions and might be a better choice!

Screenshots/Demos
I have screenshots in the folder named Screenshots of some example interactions.

Screenshot 1. Testing to see if the common ii-V-I progression works. This progression is found commonly in jazz, as the ii chord is not popular in most mainstream music, so there aren't any other potential ending chords for an inputted ii-V.

Screenshot 2. Finding potential next chord based off of just a V chord. A V chord is found in almost every piece of music and loves to resolve to a I or i chord. I'm testing this to find the frequency of how often it resolves to I or i versus to a different chord.

Screenshot 3. Testing an uncommon chord progression (III-V-VI) and getting denied, then having it search based just on the last chord (VI). Since this chord progression is never used, this serves as a test to see how well the failsafe of searching just using the last chord works.

Tree Implementation Details
Brief explanation of how your tree works
Time/space complexity of key operations
Any interesting implementation choices
Evolution of the Interface
What changed from your initial design?
Why did you need those changes?
What did you learn from this iterative process?
Challenges & Solutions
What was hard?
How did you solve tough problems?
Future Enhancements
What would you add with more time?
