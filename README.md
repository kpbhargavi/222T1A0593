# Client-side URL Shortener

A simple client-side URL shortener built using **HTML, CSS, and JavaScript**. This project allows you to shorten URLs, track clicks, and store them locally in the browser using `localStorage`.

---

## Features

- Shorten long URLs with a generated short ID.
- Track the number of clicks on each short URL.
- View the list of all created URLs along with creation date and click count.
- Copy the short URL to the clipboard.
- Redirect to the original URL when accessing the short URL via hash (`#shortId`).
- Fully client-side, no backend required.

---

## Demo

You can open the `index.html` file in your browser to test the app locally.

---

## How It Works

1. Enter a long URL in the input field.
2. Click **Shorten**.
3. A short URL is generated and displayed at the top.
4. All URLs are saved in `localStorage` with:
   - Short ID
   - Original URL
   - Click count
   - Creation date
5. Clicking on the short URL or copying it allows sharing.
6. Visiting the short URL (e.g., `http://localhost:5500/#abc123`) will open the original URL in a new tab and increase the click count.

---

## Technologies Used

- HTML
- CSS
- JavaScript (ES6)
- Browser `localStorage`

---

## Installation

1. Clone this repository:

```bash
git clone https://github.com/your-username/url-shortener.git
