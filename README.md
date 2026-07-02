# Rishit Dhote

**Backend & Distributed Systems Engineer** — currently shipping realtime trading infrastructure at **Apeing Labs**.

I build high-concurrency backends and realtime systems that stay fast under load — Rust (Tokio · Axum · SQLx) services, WebSocket fanout, and the React/TypeScript interfaces on top.

### Recent results

- Raised init-payload delivery **89% → 99% at 1,000 concurrent users/replica** — K6 load tests surfaced the bottleneck, refactor fixed it
- **Sub-second price fanout** across replicas via shared Redis pub/sub — 30+ event types multiplexed over one socket
- Ran EDA over **billions of order records** at the **National Stock Exchange**
- Built custom consensus mechanisms in **Rust/Substrate** for composable chain infrastructure

### Selected work

| Project | What it is |
|---|---|
| [cc-meter](https://github.com/Ripperox/cc-meter) | Cross-session usage observability for Claude Code — live status line + trends report |
| [llm-gateway](https://github.com/Ripperox/llm-gateway) | Transparent streaming proxy — relays SSE byte-for-byte while instrumenting TTFT/latency/throughput live |
| [flavourscout](https://github.com/Ripperox/flavourscout) | Provably-optimal cart & coupon optimizer — multiple-choice knapsack DP, 500-test suite |
| [blockchain_simulation](https://github.com/Ripperox/blockchain_simulation) | Realtime blockchain simulator — live PoW mining, mempool, 3-node P2P network |
| [rishit-portfolio](https://github.com/Ripperox/rishit-portfolio) | Interactive tech-noir portfolio with live demos — [rishitdhote.vercel.app](https://rishitdhote.vercel.app) |

### Elsewhere

**[Portfolio](https://rishitdhote.vercel.app)** · **[LinkedIn](https://www.linkedin.com/in/rishit-dhote)** · **rishitrdhote@gmail.com**

> Public repos are side work — production commits live in private org repos.
