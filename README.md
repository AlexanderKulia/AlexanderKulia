# Hi, I'm Alexander

Backend engineer in Munich. Work is mostly Python and TypeScript on top of PostgreSQL: data modeling, migrations on live systems, hunting down slow queries, and tracing that makes problems easy to find.

Free time goes into Go and Rust.

## Projects

**[wattflow](https://github.com/AlexanderKulia/wattflow)** (Go)
A pipeline that ingests energy telemetry and aggregates it per device. Events can arrive late, out of order or more than once, and the results still come out exactly the same. A replay harness tests that guarantee, and profiling shows where time and memory actually go. The README has the full story.

**[playlist-tools](https://github.com/AlexanderKulia/playlist-tools)** (Rust)
A small web app that finds and removes duplicate tracks in Spotify playlists. Spotify login via OAuth, htmx frontend, runs in Docker.

## Things that matter to me

- Automated checks that catch mistakes before a reviewer has to
- Profiling first, optimizing second
- Fixing the root cause instead of the symptom
- Writing down why a decision was made
