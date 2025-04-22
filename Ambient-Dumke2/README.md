# Ambient Dumke 2

## Project Overview
Ambient Dumke 2 is an interactive audio project that utilizes the Tone.js library to create a dynamic sound experience. The project features various audio samples, including drifting drones and upright piano sounds, which can be triggered randomly to create ambient music.

## Project Structure
The project consists of the following files and directories:

- **index.html**: The main HTML document that sets up the audio sampling and playback functionality using JavaScript and the Tone.js library.
  
- **driftDrones/**: This directory contains audio files used by the sampler, including:
  - `driftingC.wav`: Audio file for the note C0.
  - `driftingDflat.wav`: Audio file for the note C#0.
  - `driftingF.wav`: Audio file for the note G1.
  - Additional audio files as indicated by the ellipsis.

- **vsco2-ce/upright-piano/**: This directory contains audio files for the upright piano sampler, including:
  - `a0.wav`: Audio file for the note A0.
  - `csharp1.wav`: Audio file for the note C#1.
  - `f1.wav`: Audio file for the note F1.
  - Additional audio files as indicated by the ellipsis.

- **oneShots/**: This directory contains one-shot audio files, including:
  - `oS1.wav`: First one-shot audio file.
  - `oS2.wav`: Second one-shot audio file.
  - `oS3.wav`: Third one-shot audio file.
  - `oS4.wav`: Fourth one-shot audio file.
  - Additional audio files as indicated by the ellipsis.

- **README.md**: This documentation file contains setup instructions and usage details for the project.

## Setup Instructions
To run this project locally, follow these steps:

1. **Clone the Repository**: Clone the repository to your local machine using:
   ```
   git clone https://github.com/<USERNAME>/Ambient-Dumke2.git
   ```

2. **Open index.html**: Open the `index.html` file in a web browser to start interacting with the audio samples.

3. **Audio Files**: Ensure that all audio files are correctly referenced in the `index.html` for them to work properly.

## Publishing to GitHub Pages
To publish this project to GitHub Pages, follow these steps:

1. **Create a GitHub Repository**: Go to GitHub and create a new repository named `Ambient-Dumke2`.

2. **Initialize Git in Your Project**: Open a terminal in your project directory and run:
   ```
   git init
   git add .
   git commit -m "Initial commit"
   ```

3. **Link Your Local Repository to GitHub**: Run the following command, replacing `<USERNAME>` with your GitHub username:
   ```
   git remote add origin https://github.com/<USERNAME>/Ambient-Dumke2.git
   ```

4. **Push Your Code to GitHub**: Run:
   ```
   git push -u origin master
   ```

5. **Enable GitHub Pages**: Go to the repository settings on GitHub, scroll down to the "GitHub Pages" section, and select the `master` branch as the source. Save the changes.

6. **Access Your Published Site**: After a few minutes, your site will be available at `https://<USERNAME>.github.io/Ambient-Dumke2`.

## Acknowledgments
This project utilizes the Tone.js library for audio synthesis and manipulation. For more information, visit the [Tone.js website](https://tonejs.github.io/).