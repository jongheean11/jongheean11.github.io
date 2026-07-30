# jongheean11.github.io

Personal academic homepage of **James Hun Kim (Junghun James Kim)** — AI Researcher & Engineer.

Built as a static HTML/CSS site (design inspired by [Jon Barron](https://jonbarron.info/)'s template).

## Structure

- `index.html` — main page (bio, news, publications, experience, patents, education)
- `stylesheet.css` — all styles
- `files/CV_JamesHKim.pdf` — CV
- `files/photo.jpg` — profile photo (white studio background blended into a pastel-blue
  gradient; regenerate with a multiply blend if the photo changes)
- `files/pub/` — publication thumbnails

The photo is displayed as a 180×180 circle (`border-radius: 50%` in `stylesheet.css`).

## Visitor stats

Pages load an invisible [GoatCounter](https://www.goatcounter.com/) tracker
(`jongheean11.goatcounter.com`, no cookies, nothing shown on the site).
A daily GitHub Action (`.github/workflows/traffic.yml`) fetches the cumulative
visit counts and appends a row to `traffic/visitors.csv`
(`date,home,publications,projects`) — check that file (or the GoatCounter
dashboard) to see traffic over time.
