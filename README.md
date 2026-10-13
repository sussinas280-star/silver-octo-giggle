# WooMap Next

WooMap is a real-time mapping platform for viewing locations,
creating buildings, and managing addresses.

## Technology

- React
- TypeScript
- Vite
- MapLibre GL JS
- Supabase Auth
- Supabase Postgres and PostGIS
- Supabase Realtime
- Cloudflare Pages

## Features in this starter

- Interactive map
- Select locations by clicking the map
- Register and sign in with email and password
- Create buildings and map markers
- Create address records and associate them with buildings
- Publish or hide buildings you own
- Delete buildings you own
- Refresh map data when database records change
- Database row-level security policies
- GitHub Actions build workflow

## Requirements

- Node.js 22
- npm
- A Supabase project
- A GitHub account
- A Cloudflare account for deployment

## Run locally

1. Clone the repository.
2. Install dependencies.
3. Create a `.env` file based on `.env.example`.
4. Add your Supabase project URL and publishable key.
5. Run the development server.

```bash
npm install
cp .env.example .env
npm run dev
