# ChromaQuest

Chroma Quest
✨ Chroma Quest is a vibrant, single-player web game built with HTML, JavaScript, and Tailwind CSS. Dive into the magical realm of Chromaria, where you play as Lira, a shard-seer tasked with restoring the shattered Chroma Crystal. Match colorful shards in a 4x4 grid to harness their energy, guided by Elder Varyn’s witty wisdom, across two thrilling modes: Quest Mode (a 5-chapter saga) and High Score Mode (an endless challenge with power-ups).

✨ Features
Immersive Story: Explore Chromaria’s lore through a rich narrative in the “Saga of Chromaria,” rendered with Markdown.
Dynamic Gameplay:
Quest Mode: Progress through 5 chapters (Red, Blue, Green, Yellow, Purple Fields), each with unique timers, speeds, and score thresholds.
High Score Mode: Chase the top score with power-ups like Slow Grid (+200ms) and Extra Time (+5s) after 20 points.
Responsive Design: Optimized for mobile and desktop with touch and mouse support, using Tailwind CSS for a sleek UI.
Audio Experience: Toggleable background music and story tracks enhance the atmosphere (SoundHelix and Incompetech sources).
Leaderboard: Save high scores locally with 3-letter initials for competitive fun.
Accessibility: Touch-friendly controls (touch-action: manipulation), no scrolling issues (overscroll-behavior: none), and clear visuals.

🛠️ Technologies
HTML5: Structure for game screens (splash, intro, menu, game, story, victory, leaderboard).
JavaScript: Core logic for grid updates, timers, scoring, power-ups, and audio management.
Tailwind CSS: Styling for gradients, animations (fadeIn), and responsive layouts (max-w-md, min-h-screen).
Marked.js: Renders Markdown for the story screen.
LocalStorage: Persists high scores, difficulty, and leaderboard data.

🚀 Getting Started
Clone the Repository:
git clone https://github.com/your-username/chroma-quest.git
Serve Locally:
cd chroma-quest
python -m http.server 8000
Open http://localhost:8000/chroma_quest.html in a browser.
Deploy to GitHub Pages:
Push chroma_quest.html to the gh-pages branch.
Access at https://your-username.github.io/chroma-quest/.
🎮 How to Play
Objective: Tap tiles matching the target color to score points. Avoid mismatches (-2s penalty).
Quest Mode: Complete 5 chapters by meeting score thresholds (e.g., 50 on Normal). Each chapter increases difficulty.
High Score Mode: Survive as long as possible, grabbing yellow star tiles for power-ups after 20 points.
Controls:
Touch/click tiles and buttons.
Hover buttons for visual feedback (e.g., hover:bg-blue-600).
Mute audio via the speaker icon.
Difficulty: Choose Easy, Normal, or Hard to adjust timers, speeds, and thresholds.
📸 Screenshots
Splash Screen: Vibrant intro with a prismatic logo.
Game Screen: 4x4 grid with real-time score, timer, and Varyn’s flavor text.
Story Screen: Scrollable lore with a clean, white background (max-height: 70vh).
Victory Screen: Celebrates Lira’s triumph with a call to new adventures.

🤝 Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a feature branch (git checkout -b feature/YourFeature).
Commit changes (git commit -m "Add YourFeature").
Push to the branch (git push origin feature/YourFeature).
Open a Pull Request.
Please ensure code follows the existing style (e.g., Tailwind classes, modular JS functions) and test thoroughly.

🐛 Issues
Report bugs or suggest enhancements via GitHub Issues. Include:

Browser and device details.
Steps to reproduce.
Screenshots or console logs.

📜 License
This project is licensed under the MIT License. See LICENSE for details.

🙏 Acknowledgments
SoundHelix: Background music (SoundHelix-Song-1.mp3).
Incompetech: Story music (Folk Round.mp3).
Tailwind CSS: For rapid, responsive styling.
Marked.js: For Markdown parsing.

🌟 Join Lira and Varyn to save Chromaria! Match the shards, restore the Crystal, and weave your legend in Chroma Quest. 🌟
