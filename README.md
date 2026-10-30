# Make Life Funny

Make Life Funny is a small, cheerful website for adding a little curiosity and confidence-building fun to the day. From the home page, visitors can choose between two random generators: one suggests a word to explore, and the other offers a practical social or everyday challenge.

## Purpose

The project is designed to make it easy to try something new:

- **Random word** picks a word or topic to learn about. The page suggests spending 10 minutes learning about it, then speaking about it for two minutes and recording yourself.
- **Practice recording** on the Random word page requests camera and microphone access, shows an elapsed-time counter while recording, and lets you replay, download, or delete the video. The page does not upload recordings.
- **Random things** suggests a small confidence-building challenge, such as starting a friendly conversation or trying a familiar public activity.
- Both generators show a new suggestion when their button is clicked. They avoid immediately repeating the previous suggestion when there is more than one item.

Challenges are suggestions, not requirements. Choose a safe, familiar setting, keep your phone accessible, and skip anything that feels uncomfortable.

## Technologies

- **HTML5** provides the home page and the two generator pages.
- **CSS3** provides the responsive layout, colors, cards, and interactive styling.
- **Vanilla JavaScript** stores the suggestions and selects one at random when a button is clicked.

The project does not use a JavaScript framework, external library, package manager, database, or build system. Its files are served directly by a browser, so no compilation or dependency installation is required.
Camera recording requires browser permission and a secure context, such as HTTPS or `localhost`. Browsers cannot open the operating system's standalone Camera app from a webpage.

## Project files

| File | Purpose |
| --- | --- |
| `index.html` | Home page with links to both generators |
| `randomWord.html` | Random word generator page |
| `randomThink.html` | Random challenge generator page |
| `style.css` | Shared styles for all pages |
| `script.js` | Word and challenge lists, and the random-selection behavior |

## Run it on your PC

### Option 1: Open it directly

1. Download or copy the project folder to your PC.
2. Keep the HTML, CSS, and JavaScript files together in the same folder.
3. Open the folder in File Explorer.
4. Double-click `index.html`. It should open in your default web browser.
5. Choose **Random word** or **Random things**, then click the button to get a suggestion.

No installation is needed for this option.

### Option 2: Open it in Visual Studio Code

1. Install [Visual Studio Code](https://code.visualstudio.com/) if it is not already installed.
2. In VS Code, select **File > Open Folder...** and choose the project folder.
3. Open `index.html` in a browser. You can do this from File Explorer, or use a local preview extension such as Live Server if you have it installed.
4. If using Live Server, right-click `index.html`, choose **Open with Live Server**, and use the local address it opens.

Live Server is optional; the project has no required VS Code extensions.

## Customize the suggestions

To add or change words and challenges, edit the corresponding `word` or `thing` list in `script.js`. Save the file and reload the page in your browser to see the changes.