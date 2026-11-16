# Multiply Rush ⚡

A fun, responsive multiplication speed game for practising the 12 through 20 tables.

## Features
- Choose 50, 100, 150 or unlimited questions per challenge
- 5-second timer for every question
- Live score, accuracy, current streak and best streak
- Keyboard-friendly answer input (press Enter)
- Pause/resume, sound toggle, reset and replay
- Responsive desktop and mobile layout
- No build tools or dependencies required

## Run locally
Open `index.html` in any modern browser.

## Deploy with GitHub Pages
1. Create a new GitHub repository, e.g. `multiply-rush`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for deployment. GitHub will show your live Pages URL.

It will look like `https://YOUR-USERNAME.github.io/multiply-rush/`.

## Customize
In `index.html`:
- Change `TOTAL=150` to change the number of questions.
- Change `LIMIT=5000` to change the timer (milliseconds).
- The game currently uses tables 12 through 20. Edit the table range in `make()` to customize it.
