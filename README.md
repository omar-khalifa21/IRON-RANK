# IronRank

Verified powerlifting leaderboards for lifters and gyms — city, country, continent, world.

## What it is

IronRank lets lifters post their squat/bench/deadlift PRs, get them verified, 
and see their rank across multiple geographic scopes. Gyms are ranked by their 
top lifters' combined totals.

Verification uses an ML-weighted community voting system — votes from higher-ranked, 
more established lifters carry more weight.

## Tech Stack

- **Backend**: FastAPI + PostgreSQL + SQLAlchemy
- **Frontend**: React
- **Video Storage**: Cloudflare R2
- **Hosting**: Hetzner CX33

## Features

- PR submission with video proof
- ML-weighted community verification
- Leaderboards by SBD total, Wilks, or DOTS
- Scopes: city → country → continent → world
- Categories: raw, equipped, U18, best physique
- Gym leaderboards (combined top lifter totals)
- Shareable rank cards
- Badges and sponsored challenges

## Monetization

- Gym subscriptions (~$20–50/month)
- Lifter premium tier (~$3–5/month)
- Sponsored challenges

## Status

In development. Payment functionality targeting July launch.
