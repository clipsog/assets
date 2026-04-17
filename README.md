# clipsog / assets

Static assets (logos, images, icons) for clipsog apps. Host this repo on **Render** as a static site or use **GitHub raw URLs** until then.

## Layout

| Path | Description |
|------|-------------|
| `hoopify/logo.png` | Hoopify brand logo |

Add more folders per app or shared `common/` as needed.

## URLs (GitHub)

After push, stable raw links (replace `main` with your default branch if different):

- **Hoopify logo:** `https://raw.githubusercontent.com/clipsog/assets/main/hoopify/logo.png`

Use these in HTML/CSS/JS, or point a CDN (e.g. jsDelivr) at the same path if you prefer caching.

## Render (next step)

Deploy as a **Static Site**: root directory `/`, build command empty, publish directory `.`. Set the public URL in each app’s config for production asset base URL.

## Supabase (later)

Application data (users, bookings, etc.) lives in Supabase Postgres—not in this repo. This repo is **files only**.
