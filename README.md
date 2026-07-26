# Fahrplan

Your personal companion to the German driving licence — progress tracking, costs,
maneuvers, road signs, phrases and a local forum.

## Hosting on GitHub Pages

1. Create a new repository on GitHub (e.g. `fahrplan`), public.
2. Upload the contents of this folder (`index.html`, `.nojekyll`, this README) to the repo root.
3. Repo → **Settings** → **Pages** → Source: *Deploy from a branch* → Branch: `main`, folder: `/ (root)` → Save.
4. After ~1 minute the app is live at `https://<your-username>.github.io/<repo>/`.

GitHub Pages serves over HTTPS, which the "find a Sehtest / Fahrschule near you"
geolocation feature requires.

## Notes

`index.html` is fully self-contained (app, data and fonts inlined) and works offline.
Accounts, Google sign-in and emails are local simulations — real authentication
requires a backend (e.g. Firebase Auth or Supabase).
