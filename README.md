# MoneyFlow Web Ready — Supabase

MoneyFlow is a browser-based finance tracker using Supabase Auth + PostgreSQL. It is designed for deployment to Vercel or any static hosting.

## Supabase already configured
The frontend is configured for the Supabase project supplied during setup. The SQL schema must be created in Supabase SQL Editor first.

## Deploy
1. Upload this folder to a GitHub repository.
2. Import the repository into Vercel.
3. No build command is required; the site is static.
4. Deploy and open the generated URL.

## Important
For production, configure Supabase Auth email/redirect settings for your deployed domain. Do not expose a Supabase secret/service-role key in the browser. The browser uses the publishable key only.
