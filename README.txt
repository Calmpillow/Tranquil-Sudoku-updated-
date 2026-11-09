TRANQUIL SUDOKU — UPDATED OFFLINE / GITHUB PAGES VERSION

WHAT'S NEW
- 20 peaceful animated color themes, each with its own base palette and gentle motion.
- Themes automatically change with each level, or players can choose and keep a favorite.
- Four puzzle difficulties: Easy, Normal, Hard, and Extreme.
- A short animated, interactive Sudoku guide appears before a new player's first level.
- The guide can be replayed at any time with the Guide button.
- Existing local username profiles and game progress are retained when the browser can read the old save.

UPLOAD
1. Extract this ZIP.
2. Upload the CONTENTS of the tranquil-local folder (index.html, manifest.webmanifest, sw.js, icon.svg, README.txt) to the ROOT of your GitHub repository.
3. Replace the previous files when GitHub asks.
4. In GitHub repository Settings > Pages, choose Deploy from a branch, branch main, folder /(root), then Save.
5. Open or refresh the GitHub Pages URL. If an older installed copy appears, close it and reopen after the service worker refreshes.

PLAYER SAVES
Each player enters a username. Progress, difficulty, and theme preferences are saved in that browser on that device. Different usernames have separate saves. These are local browser saves, not cloud accounts, and do not sync between devices. Clearing browser data can erase local saves.

DIFFICULTY
Easy gives more starting numbers; Normal is the balanced default; Hard and Extreme remove more starting numbers. Changing difficulty starts a fresh puzzle at the current level after confirmation.

THEMES
Automatic mode changes to a different theme on every level. Manual mode lets a player select one of the 20 palettes. The 20 illustrated SVG background scenes are included in the themes folder. Gentle particles and light effects animate over them; no external image downloads or internet connection are needed after the game is loaded.

ACCESSIBILITY
Animations are subtle and automatically reduced when the device has Reduce Motion enabled.
