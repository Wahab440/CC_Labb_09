# Task App
This is a React + Vite task app that uses Supabase for auth and data storage.

## Local setup

1. Copy [.env.example](.env.example) to [.env.local](.env.local).
2. Fill in your Supabase project URL and anon key.
3. Run `npm install` if dependencies are not installed yet.
4. Start the app with `npm run dev`.

## Supabase setup

1. Create a Supabase project.
2. Create a `tasks` table that matches the fields used by the app.
3. Enable Auth providers you want to support, usually email/password.
4. Add your production URL to the Supabase Auth redirect URLs.
5. Use the project URL and anon key in your frontend environment variables.

## GitHub and deployment

1. Commit and push this repository to GitHub.
2. Connect the GitHub repo to your deployment platform of choice, such as Vercel or Netlify, for the frontend.
3. Set `VITE_SUPABASE_URL` and `VITE_SUPABASE_ANON_KEY` in the platform environment settings.
4. Redeploy after changing environment variables.

## Production build

Run `npm run build` before deployment to verify the app compiles cleanly.
