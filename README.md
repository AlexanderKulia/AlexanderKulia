# Alexander Kulia

Backend engineer in Munich. I work on systems where a wrong number is worse than a slow one: domain modeling, PostgreSQL, data migrations on live data, and enough observability to know why something broke instead of guessing.

Day to day that means Python and TypeScript. On my own time I build in Go and Rust.

## Projects

### [wattflow](https://github.com/AlexanderKulia/wattflow) (Go)
An energy telemetry ingestion pipeline built around one invariant: for a fixed set of events, the per-device aggregates are bitwise-identical no matter the delivery order or how many duplicates arrive. It covers deduplication, watermarks with a bounded lateness window, an explicit backpressure policy, batched writes to TimescaleDB, and OpenTelemetry tracing across every stage.

A replay harness tests the invariant against reordered, duplicated and mixed delivery. The throughput ceiling comes from a measured config sweep, and allocation fixes come from pprof data. The full profiling narrative is in the repo.

### [playlist-tools](https://github.com/AlexanderKulia/playlist-tools) (Rust)
Finds and removes duplicates in Spotify playlists. OAuth flow, a small htmx UI, runs in Docker.

## How I like to work

- Make correctness checkable by a machine, not by "we tested it"
- Measure before optimizing, and find the real bottleneck before adding hardware
- When a problem keeps coming back, fix the class of bug, not the instance
- Write the decision down, including the arguments against it

## Contact

[LinkedIn](https://www.linkedin.com/in/alexanderkulia)
