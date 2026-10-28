# A-Silent-Voice
Run npm install and npm run dev. Build: npm run build.
Images and film facts: https://gkids.com/films/a-silent-voice/ and https://koenokatachi-movie.com/
Video source: user upload, 1280x720. Desktop background upscaled to 3840x2160; not native 4K. Gallery download copies resized from 1998x1080 to 3840x2160. Mobile background is 720p. All film images belong to their respective owners. React + Vite.

Background videos include the original uploaded audio track. Tap Qo‘shiqni yoqish to enable it. Audio and video remain synchronized and loop together. Opening a YouTube trailer mutes the background; closing it restores the selected sound setting.

## Navbar and view counter
Telegram: https://t.me/Iego_oI . The counter uses Netlify Functions and a site-wide Netlify Blobs store. One anonymous UUID per tab session is counted; page reloads in the same tab do not add another visit. No IP or personal details are stored. The count starts after this feature is deployed; previous visits are not recoverable. Deploy from GitHub using the included netlify.toml so the function is built; a static-only Drop upload does not deploy this counter. Locally use Netlify Dev for the function. If the endpoint is unavailable, the navbar shows — rather than an invented number.
