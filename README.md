# my_landing

Static single-page site — no build step, no dependencies.

## Files
- `index.html` — the whole site (HTML + CSS + JS inline). Fonts load from Google Fonts.
- `vercel.json` — static config (clean URLs, long-lived asset caching).

## Deploy to Vercel

```bash
cd ~/Рабочий\ стол/projects/my_landing
npx vercel          # preview deploy
npx vercel --prod   # production
```

Or: push this folder to a GitHub repo → vercel.com → New Project → import it.
Framework preset: **Other**. Build command: none. Output directory: `./`.

## Editing
- Links: the `<a class="card" href="…">` block in `#links`. Discord href is still `#` — paste your user ID URL.
- Bio: the `script` array near the top of the `<script>` block (`cat about.txt` lines).
- Typing speed: `var SPEED = 52;` (ms per character).
- Colors: the `:root` custom properties at the top of `<style>` — `--accent` is the acid yellow-green.
- Stack badges: the `.badges` rows in `#stack`.
