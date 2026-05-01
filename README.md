You'll need to compile background.ts to background.js (Chrome requires .js files)
Update manifest.json to reference background.js as the service worker
Create placeholder icon files (icon16.png, icon48.png, icon128.png) or remove the icons section from manifest.json
Load the extension in Chrome by going to chrome://extensions/, enabling Developer Mode, and clicking "Load unpacked"
The extension will automatically open a new tab whenever it detects that no chrome://newtab/ page exists, checking every 10 seconds.

