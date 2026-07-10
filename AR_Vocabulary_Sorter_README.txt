AR VOCABULARY SORTER
====================

FILES
- ar_vocab_sorter.html: the complete game in one file.

QUICK USE
1. Open ar_vocab_sorter.html in Chrome, Edge, Firefox, or Safari.
2. Press "Start with Camera" and allow camera permission.
3. Pinch your thumb and index finger together over the card.
4. Keep pinching while moving the card, then open your fingers over a box.
5. Mouse and touchscreen dragging work without a camera.

EDITING THE ACTIVITY
1. Press the gear button.
2. Rename the three category boxes.
3. Choose each box's emoji and color.
4. Enter one vocabulary item per line.
5. Add an optional visual hint after a vertical line, for example:
   Apple | 🍎
6. Press "Save & Start."

SAVE AND SHARE ACTIVITIES
- Settings are saved automatically in that browser.
- "Export activity" creates a small JSON preset.
- "Import activity" loads a preset made on another device.

CAMERA REQUIREMENTS
The browser must allow camera access. For the most reliable camera support, serve the file from HTTPS or localhost.

EASY LOCAL SERVER (COMPUTER)
If Python is installed, open a terminal in the file's folder and run:

  python -m http.server 8000

Then open:

  http://localhost:8000/ar_vocab_sorter.html

PHONE / TABLET
Upload ar_vocab_sorter.html to any HTTPS static website host, such as a school website or GitHub Pages, then open the web address on the phone. Allow camera permission.

PRIVACY
The camera frames are processed locally in the browser by MediaPipe. The game itself contains no upload or recording code.

INTERNET CONNECTION
Hand tracking loads Google's MediaPipe library and hand model from online CDNs, so camera gesture control needs an internet connection when it starts. Mouse/touch play works even when the hand-tracking library cannot load.
