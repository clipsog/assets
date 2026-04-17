# clipsog / assets

Static assets for **Value Scheduler** (the scheduler platform) and other clipsog apps. Use **GitHub raw URLs** or host this repo as a **Render** static site.

## Value Scheduler (`value-scheduler/`)

| File | Description |
|------|-------------|
| `value-scheduler/favicon.svg` | App favicon |
| `value-scheduler/icons.svg` | Icon sprite / set used by the app |

These files mirror the Value Scheduler app’s `public/` directory so you can point production builds at fixed URLs.

### Raw URLs (GitHub, branch `main`)

- `https://raw.githubusercontent.com/clipsog/assets/main/value-scheduler/favicon.svg`
- `https://raw.githubusercontent.com/clipsog/assets/main/value-scheduler/icons.svg`

## Render & Supabase

- **Render:** deploy this repo as a static site and use that origin in the scheduler app for production asset URLs.
- **Supabase:** application data is separate; this repo holds **static files only**.
