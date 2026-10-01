# Barcelona Rock & Underground Bars

A single-file static site for a Barcelona trip. It includes a venue shortlist, Google Maps links, area filtering, and optional browser geolocation to sort venues by approximate distance.

## Publish free with GitHub Pages

1. Sign in to GitHub and create a new public repository, for example `barcelona-rock-bars`.
2. Upload `index.html` from this folder to the repository root and commit it.
3. Open the repository's **Settings** → **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main**, folder **/(root)**, then Save.
6. After GitHub finishes deploying, the Pages section will show the public URL. It will usually look like `https://YOUR-USERNAME.github.io/barcelona-rock-bars/`.

GitHub Pages serves the site over HTTPS, which is required by modern mobile browsers for geolocation. When you tap “Sort by distance,” the browser asks for permission. The site does not upload or store your location.

## Edit the list

Open `index.html` in a text editor. Near the bottom is `const venues = [...]`. Each venue has its name, area, address, coordinates, description, status and website. After editing, commit the updated file to GitHub and Pages will redeploy automatically.

## Venue notes checked around October 2026

The current build includes Nevermind, Manchester Bar, Hell Awaits, Motor Oil Cocktail Garage, Magic Rock Club, Meteoro, Psycho Rock 'n' Roll Club, La Deskomunal, Undead Dark Club, Sala Apolo, Bar Ceferino, Sala Bóveda, Puerto Hurraco Sisters, Estraperlo Club del Ritme and Ateneu Popular 9 Barris.

Bollocks Rock Bar is omitted because a 2026 update reports it permanently closed; Motor Oil Cocktail Garage now occupies the same Carrer Ample 46 address. Sala Bóveda is kept in the list but marked temporarily closed. Puerto Hurraco Sisters is marked with a member-space caveat. Venue schedules can change, so the Google Maps and venue-site links are intended for a final check on the day.
