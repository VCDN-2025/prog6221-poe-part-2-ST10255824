# prog6221-poe-part-2-ST10255824
prog6221-poe-part-2-ST10255824 created by GitHub Classroom


Welcome to the Cybersecurity Awareness Bot — a retro-themed, voice-greeting, joke-filled console chatbot built in C#. Designed to teach users about cybersecurity basics in a fun and informative way!

## project structure
```plaintext
Cybersecurity-Awareness-Bot/
├── Program.cs             # Main chatbot logic
├── greeting.wav           # Voice greeting file (WAV)
├── README.md              # Project overview and setup
└── .github/
    └── workflows/
        └── dotnet.yml     # GitHub Actions for Continuous Integration (CI)
```

## Requirements
To run this project successfully, you'll need:

- Visual Studio 2022 or later / Visual Studio Code
- .NET 6 SDK or later
- `greeting.wav` (place it in the same directory as `Program.cs` or your compiled `.exe`)

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/VCDN-2025/prog6221-poe-part-2-ST10255824.git
   ```
2. Open the project in Visual Studio or VS Code.
3. Make sure `greeting.wav` is in the correct folder.
4. Build and run.

## Features 
-  **Retro Console UI**: Uses colored console output with a retro-inspired theme.
-  **Voice Greeting**: Plays a WAV file greeting when the chatbot starts.
-  **ASCII Art Logo**: Displays a welcome banner in stylized ASCII art.
-  **Interactive Conversation**: Users can ask cybersecurity-related questions.
-  **Keyword Recognition**: Detects keywords like "passwords", "vpn", "phishing", etc., and gives relevant advice.
-  **Randomized Responses**: For general questions like "how are you", the bot responds with varied phrases.
-  **Help Command**: Lists available topics and guidance.
-  **Memory & Recall**: Remembers the user's name during the session.
-  **Basic Sentiment Detection**: Reacts differently to positive vs. negative inputs like "bad", "good", etc.
-  **Error Handling**: Handles unrecognized inputs gracefully.
- 🛠 **Extensible Code Structure**: Easy to expand with new features or topics.

## help command
Type any of these during the conversation:

- `how are you` – Feeling curious?
- `what's your purpose` – Learn my job.
- `passwords` – Tips for secure passwords.
- `phishing` – Spot fake emails & scams.
- `antivirus` – Keep the baddies away.
- `public wifi` – Risky biz in coffee shops.
- `vpn` – Ninja-mode activated.
- `2FA` / `authentication` – Double lock your accounts.
- `social media` – Think before you post.
- `scam emails` – Recognize & avoid them.
- `software updates` – No more 'remind me later'.
- `cookies` – They're watching.
- `exit` / `quit` / `bye` – End the convo.
