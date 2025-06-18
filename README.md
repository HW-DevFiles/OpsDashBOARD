#OpsDashBOARD

Real time infrastructure dashboard built with Supabase, Next.js, and cursed energy. Monitors fake metrics like latency, error rate, and build status. Built in 48 hours of desperation and caffeine.

## Features
- Real time metrics updates
- Supabase DB + subscriptions
- Custom metric simulator
- Sleek dark-mode UI
- Zero authentication, pure chaos

## Tech Stack
- Supabase (PostgreSQL, Realtime)
- Next.js + Tailwind CSS
- Node.js for simulator
- Vercel for deployment

## Setup
1. Clone the repo
2. Set up Supabase and create the `fake_metrics` table (schema inside)
3. Run the simulator: `node simulator/index.js`
4. Start frontend: `npm run dev` in `ops-dashboard-frontend`

## License
MIT, because who’s going to sue me for fake metrics?
