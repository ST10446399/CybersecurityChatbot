# CybersecurityChatbot
# 🛡️ Cybersecurity Awareness Chatbot

A simple C# console-based chatbot designed to help users learn about cybersecurity best practices like password safety, phishing, and safe browsing.

## 🎯 Features

- 🔊 **Voice Greeting** – Plays a welcome message on startup.
- 🖼️ **ASCII Art Display** – Displays a logo or symbol using ASCII.
- 💬 **User Interaction** – Asks for your name and personalizes responses.
- 🔐 **Cybersecurity Q&A** – Responds to questions about online safety.
- ✅ **Input Validation** – Handles invalid or empty inputs gracefully.
- 🎨 **Enhanced Console UI** – Uses borders, colors, and effects for a better experience.
- 🔄 **GitHub Actions CI** – Automatically builds and checks your project with every push.

## 🛠️ Requirements

- .NET SDK 7.0 or later
- Windows (for audio playback using `System.Media`)

## 🚀 How to Run

1. Clone the repository
2. Open in Visual Studio or VS Code
3. Build and run the project

```
dotnet run
```

## 🔊 Adding Voice Greeting

Make sure you have `welcome.wav` in the project directory and set its properties to:
- **Build Action**: `Content`
- **Copy to Output Directory**: `Copy if newer`

## 🤖 Sample Questions to Try

- How are you?
- What's your purpose?
- Tell me about password safety
- What is phishing?
- How can I browse safely?

## ✅ GitHub Actions CI

This repo includes a `.github/workflows/dotnet.yml` file that checks your project builds correctly on every push.

---

Created by a Varsity College student as part of a cybersecurity awareness project.

