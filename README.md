# Magellan

A daily straight-line sailing game. Ten real coastal spots a day: pick a heading, your boat sails dead straight around the curve of the Earth until it hits land, and you score against the longest voyage possible.

Ways to play: the daily voyage (same spots and rules for everyone, ranked worldwide), head-to-head duels (20,000 HP each; the shorter voyage loses the difference in km), live duels against a friend from a shared link, and practice. Spots come from a pool of 1,909 real coastal starting points.

Play: https://stevomaccork.github.io/magellan/

## Files

- `index.html` is the whole game.
- `favicon.svg`, `apple-touch-icon.png`, `icon-512.png` and `og.png` are the Magellan icon and the link-preview image.
- `config.js` holds the settings: the Supabase project for the world ranking, the date of voyage #1, and the share link. With the placeholders left in, the game runs without the ranking.

To turn on the ranking, edit `config.js` here on GitHub (pencil icon), paste the Supabase Project URL and Publishable key, and commit. The site updates within a couple of minutes.
