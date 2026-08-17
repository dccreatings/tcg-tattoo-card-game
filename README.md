# TCG-Tattoo Card Game

A platform for building a trading card game out of real tattoo artistry. Artists from around the world sign in, create a private profile, and submit designs to a shared card library. The collection owner has a Control Room to browse every artist's submissions and organize designs into card sets.

## How it works

- **Artists** sign in with Google and get their own private studio: a profile (name, bio, social links) and a design library only they and the owner can see.
- **The owner** (a single hardcoded account) additionally gets a Control Room to browse every artist's profile and designs, and to create/manage card **sets** — each with a status, progress notes, and a curated list of cards pulled from any artist's library.
- Uploaded images are compressed and stored directly in the database as web-quality previews, not print-resolution files — final production files should be collected from artists separately.

## Tech

Single static HTML file, Firebase Authentication (Google sign-in) and Firestore for data, hosted on GitHub Pages. No backend server to run or maintain.
