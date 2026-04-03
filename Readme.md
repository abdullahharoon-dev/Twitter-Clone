# Twimba - Twitter Clone

A simple Twitter-like feed built with HTML, CSS, and vanilla JavaScript.

## Overview

Twimba is a frontend mini-project where users can:
- View a list of tweets
- Like and unlike tweets
- Retweet and un-retweet tweets
- Toggle tweet replies
- Post a new tweet to the top of the feed

The project uses local mock data and renders everything on the client side.

## Features

- Dynamic tweet rendering from `data.js`
- Event delegation for all tweet actions
- Like and retweet counters with toggle states
- Reply section show/hide per tweet
- New tweet creation with unique ID generation

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES Modules)
- Font Awesome (icons)
- Google Fonts (Roboto)
- `uuid` via CDN (`https://jspm.dev/uuid`)

## Project Structure

```text
Twimba - Twitter clone/
|- index.html
|- index.css
|- index.js
|- data.js
|- images/
`- Readme.md
```

## How To Run Locally

1. Clone or download this repository.
2. Open the project folder.
3. Run with a local server (recommended), for example:

```bash
npx serve .
```

4. Open the shown local URL in your browser.

You can also open `index.html` directly, but a local server is better for module-based JavaScript projects.

## Current Behavior Notes

- Tweets are not saved to a database.
- Any new tweet exists only until page refresh.
- All initial tweets come from `data.js`.

## Future Improvements

- Persist tweets using localStorage or backend API
- Add delete/edit tweet support
- Add user authentication
- Improve responsive design for mobile and tablet

## Author

Built by Abdullah Haroon.
