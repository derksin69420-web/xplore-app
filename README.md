# Xplore

Xplore is a single-file web app that helps people new to an area discover events and activities where they are likely to meet people with similar interests naturally.

## Features

- Onboarding flow with local-only profile storage
- Personalized event feed with match dots and save/skip actions
- Saved events with status tracking from `Interested` to `Went`
- Private review flow after attended events
- Learning summary after 3+ reviews
- Demo mode with realistic events for Dallas, New York, Los Angeles, Chicago, and Austin
- Optional OpenAI-powered event generation and signup-link search

## Files

- `index.html` - the complete app with all HTML, CSS, and JavaScript inline

## Running It

Open `index.html` in a browser.

If you add an API key, the app stores it in localStorage under `xplore_openai_key` and uses the OpenAI Responses API from the browser. For a production version, you would typically proxy these requests through a backend instead of exposing the key client-side.

## Notes

- User profile data, saved events, statuses, and reviews are stored in localStorage only.
- Built with OpenAI Codex.
