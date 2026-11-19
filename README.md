# t4typing-vinay_codemy
A fast, beautiful typing speed test that runs entirely in your browser. No sign-up, no tracking, no backend. Just you and the keys.  Built with plain HTML, CSS and JavaScript in a single file.

## Live Demo

> Add your link here after deploying, for example 'https://your-vinay-005.github.io/t4typing/

## Features

- **Real-time stats:** live WPM, accuracy, mistakes and a countdown timer
- **Flexible durations:** 1, 3, 5, 10 or 30 minutes
- **Two text modes:** natural sentences or random words
- **Three difficulty levels:** Easy, Medium and Hard (capitals, numbers and punctuation)
- **Personal best and history:** your best WPM and last 5 tests are saved locally
- **Word of the Day:** a new word daily with its meaning and an example, plus a button to practice typing it
- **Light and dark themes:** your choice is remembered
- **Typing sounds:** key click and error beep, with a mute toggle
- **3D animated intro:** an animated 3D name reveal on the loading screen
- **Glassmorphism UI:** animated gradient background, responsive on desktop, tablet and mobile
- **Accessible:** keyboard friendly, focus outlines and reduced-motion support
- **Private:** everything stays in your browser, nothing you type is sent anywhere

## Getting Started

No build step or dependencies are needed.

'''bash
# Clone the repository
git clone https://github.com/your-username/t4typing.git
cd t4typing

# Open the file in your browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
'''

You can also just double-click 'index.html'.

## Deploy with GitHub Pages

1. Push the project to a GitHub repository
2. Go to **Settings → Pages**
3. Under **Source**, choose the `main` branch and the `/ (root)` folder
4. Click **Save**. Your site will be live in about a minute

## How to Use

1. Pick a time, text mode and difficulty from the sidebar
2. Click the typing box and start typing. The timer begins on your first key
3. When time is up, you will see your WPM, accuracy and mistakes

### Keyboard Shortcuts

| Key | Action |
| --- | --- |
| `Tab` | Restart the current test |
| `Esc` | Close the results popup or sidebar and start fresh |

## How WPM Is Calculated

'''
WPM = (correct characters / 5) / minutes
Accuracy = (total typed − mistakes) / total typed × 100
'''

A "word" is counted as 5 characters, which is the standard typing-test convention.

## Project Structure

```
t4typing/
├── index.html    # the whole app (HTML, CSS and JS)
└── README.md
```

## Tech Stack

- HTML5
- CSS3 (custom properties, grid, flexbox, 3D transforms, backdrop-filter)
- Vanilla JavaScript
- Web Audio API for sounds
- 'localStorage' for saved settings, best score and history
- Google Fonts: Space Grotesk and JetBrains Mono

## Customization

- **Sentences:** edit the 'S' object in the script to add your own sentences for each difficulty
- **Word list:** edit the 'W' string for random-words mode
- **Words of the Day:** add entries to the 'WD' array
- **Colors:** change the CSS variables in ':root' (and '[data-theme="light"]')
- **Intro animation:** change the name in the loader script, and adjust the '3600' timeout to change how long it plays

## Contributing

Suggestions and pull requests are welcome. Fork the repo, create a branch, make your changes and open a PR.

## License

This project is open source. Add a 'LICENSE' file (for example MIT) to the repository to make the terms clear.

## Author

**Vinay**
