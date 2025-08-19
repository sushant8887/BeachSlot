BeachSlot – Cocos Creator Slot Game
BeachSlot is a feature-rich slot machine game built with Cocos Creator 3.8.4, designed for web and desktop platforms.
The game supports landscape-only play, auto-spin mode, bonus wheel mini-game, animated paylines, and thunder effects for wins.

Features
Modern slot machine gameplay with multiple paylines and bet steps.
Auto Play Mode: Spins automatically until stopped by the user.
Bonus Wheel Panel: Triggered on bonus wins, with animated wheel and prize display.
Animated Win Effects: Thunder and bonus animations highlight winning stops.
Responsive UI: Enforces landscape mode and adapts to device orientation.
Robust error handling: Disables all buttons on API failure and shows user-friendly popups.
Persistent state: Stores player and game data in localStorage for session continuity.
Audio effects: Integrated sound for spins, wins, bonuses, and UI interactions.
Tech Stack
Cocos Creator (TypeScript)
Web/Desktop build
RESTful API integration for player and game data
How It Works
On game start, authentication tokens are read from the URL and stored.
Player and game configuration are fetched from remote APIs.
Spin, auto-spin, and bonus game logic are managed in a single controller for maintainability.
UI state (buttons, panels) is tightly controlled to prevent logic errors and ensure smooth gameplay.
Getting Started
Clone the repo and open in Cocos Creator.
Configure API endpoints and assets as needed.
Build for web or desktop and deploy.
Enjoy spinning and winning on the beach!
