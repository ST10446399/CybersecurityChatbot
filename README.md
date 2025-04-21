CyberBuddy: Your Console Companion for Cybersecurity
Features

Warm Voice Welcome – Kicks off with a friendly voice greeting to make users feel right at home.

ASCII Art Flair – Displays a cool ASCII logo or symbol on launch to set the tone.

Personalized Interaction – Asks for your name and tailors its responses for a more personal touch.

Cyber Smarts Q&A – Answers your questions on internet safety, from phishing traps to strong password habits.

Smart Input Handling – Handles blank or unexpected inputs gracefully without crashing.

Upgraded Console UI – Pops with color, borders, and special effects to make the experience more visually appealing.

Automated CI via GitHub Actions – Every code push triggers a build and check to keep things running smooth and error-free.

##  Requirements

- .NET SDK 7.0 or later
- Windows (for audio playback using System.Media)

##  How to Run

1. Clone the repository
2. Open in Visual Studio or VS Code
3. Build and run the project

dotnet run


## Adding Voice Greeting

Make sure you have welcome.wav in the project directory and set its properties to:
- **Build Action**: Content
- **Copy to Output Directory**: Copy if newer

## Sample Questions to Try

- How are you?
- What's your purpose?
- Tell me about password safety
- What is phishing?
- How can I browse safely?

## GitHub Actions CI

This repo includes a .github/workflows/dotnet.yml file that checks your project builds correctly on every push.

---

Created by a Varsity College student as part of a cybersecurity awareness project.

