# EventPulse
1. Supabase → SQL Editor → run `supabase/schema.sql`.
2. Supabase → Authentication → Providers → Email → turn OFF "Confirm email" (demo convenience).
3. Vercel → Project → Settings → Environment Variables: NEXT_PUBLIC_SUPABASE_URL, NEXT_PUBLIC_SUPABASE_ANON_KEY (see .env.example). Redeploy.
Local: `cp .env.example .env.local && npm i && npm run dev`
