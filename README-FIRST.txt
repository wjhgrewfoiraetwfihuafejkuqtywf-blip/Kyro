KYRO — START HERE

This is a fresh static website starter for KYRO.

FILES
- index.html: page structure
- style.css: layout, colors, responsive styling, themes
- script.js: navigation, local profile, game library, mini-games, Spotify embed

RUN IT
1. Keep all three files in the same folder.
2. Open index.html in a browser to preview.
3. For hosting, upload the files to a new GitHub repository and connect that repository to Cloudflare Pages.

WHAT WORKS NOW
- Responsive gaming dashboard
- Searchable game library and category filters
- Built-in playable 2048, Memory Match, and Reaction Test
- Favorite games (saved in this browser)
- Local display name and avatar initial
- Five themes and custom accent color
- Spotify search link and Spotify embed player for supported track, album, playlist, show, and episode links

SPOTIFY NOTES
- Click Search Spotify to find music on Spotify.
- Copy a Spotify link and paste it into KYRO Music.
- KYRO embeds Spotify's official player. It does not collect Spotify passwords.
- Spotify controls playback and availability. Some features may require a Spotify account, Premium, cookies, or user interaction.
- This starter does not use Spotify's Web API or provide full Spotify account OAuth. Do not put Spotify client secrets in browser JavaScript.

GAME NOTES
- The built-in mini-games are playable.
- Other cards are labeled as placeholders until you add a legitimate playable URL or obtain permission to embed the game.
- Do not use this site to bypass school, workplace, or network restrictions.

CUSTOMIZATION
- Edit the games array near the top of script.js to add or rename game cards.
- Add actual game launch/embedding logic only for sources that allow it.
- Profile, favorites, and theme settings currently save only in the current browser using localStorage. They are not online accounts yet.
