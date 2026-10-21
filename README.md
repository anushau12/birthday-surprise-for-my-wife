# Romantic birthday surprise website

Open `index.html` in a browser to preview. The website requires no build tools, backend, or libraries.

## Personalize

Open `index.html` in any text editor and search for `const CONFIG`. Change `wifeName`, `husbandName`, `birthdayMessage`, `finalMessage`, `voiceLines`, and the photo list. Keep quotes and commas valid JavaScript. The token `{husband}` in letters is replaced automatically.

## Photos

Put `photo1.jpg`, `photo2.jpg`, etc. in the `photos` folder and match their names in the `photos` list in CONFIG. Missing photos automatically show decorative illustrated placeholder cards. Clicking an available photo enlarges it.

## Music and speech

Place an optional legally obtained audio file named `music.mp3` alongside `index.html`, or change `musicPath`. Music starts only when Music on is clicked. Voice is optional, toggled with Voice on, and uses your browser's installed English speech voice. Some browsers restrict speech from hover; the dialogue is always displayed as text. Missing music never prevents the surprise.

## Free Netlify deployment

Go to https://app.netlify.com/drop and drag the entire `birthday_site` folder onto the page. Netlify will provide a public link. You can change the site name in Netlify settings.

## Free GitHub Pages deployment

Create a public GitHub repository, upload `index.html` and any optional `photos/` and `music.mp3` assets to the repository root, then open Settings > Pages > Build and deployment > Deploy from a branch. Select `main` and `/ (root)`, then save. Wait for the Pages link to appear.

## Test checklist

- Desktop: move pointer onto the button three times; each hover moves it, fourth interaction is a click.
- Mobile: tap three times; fourth tap reveals the celebration.
- Verify the button stays in view after resize or rotation.
- Try voice off/on, and missing optional music.
- Blow and relight candles, skip letter typing, tap reason cards, and open photos.
- Open and close the final surprise, then replay without refreshing.
- Check keyboard Tab/Enter access and reduced-motion settings.

Automated browser tests were not available in this environment; please test on your intended devices before sharing.
