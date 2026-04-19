<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f2937,100:533483&height=200&section=header&text=mcaney006&fontColor=ffffff&fontSize=72&fontAlignY=38&animation=fadeIn" alt="banner" />

</div>

---

## Michael Caney Jr

`mcaney006`

Backend engineer working on distributed systems, reliability, and the parts of software people only notice when they break.

📍 Dallas, Texas

---

### whoami

```ruby
me = {
  daily:     %w[Ruby Go TypeScript],
  deeper:    %w[Rails Postgres Redis OpenTelemetry],
  infra:     %w[AWS Terraform Docker GitHub-Actions],
  patterns:  %w[event-driven backpressure idempotency eventual-consistency],
  tolerate:  %w[Python], # data glue and quick wins, nothing more
  exploring: %w[Zig Rust DuckDB Bun],
  mindset:   ["reliability > hype", "systems-thinking over syntax"]
}
```

---

### what I actually do

- Build backend systems that don't collapse under real traffic
- Design APIs with clear failure modes instead of "hope it works"
- Think in terms of **latency, throughput, and failure domains**, not just features
- Spend more time on **debuggability** than "clean abstractions"
- Treat production like a hostile environment, because it is

---

### principles

- **Correctness > cleverness**
  The most dangerous engineer is the one trying to be impressive. I optimize for things that still work when nobody's watching.

- **Fail loud, not silent**
  Hidden failures are how you wake up to corrupted data and a bad week.

- **Every RPC has a budget**
  Deadlines, retries, circuit breakers. If you don't define the contract, the network will.

- **Idempotency is not optional**
  If your system can't handle retries, it's already broken.

- **Backpressure over burnout**
  Systems that can't slow down will eventually fall over.

- **Observability is a feature**
  Logs, metrics, traces. If on-call is guessing, the system is unfinished.

- **Read the source**
  Documentation lies. Code usually doesn't.

---

### systems thinking

- Prefer **simple, well-understood architectures** over trendy complexity
- Understand tradeoffs between **consistency vs availability**, not just pretend both exist
- Design for **partial failure**, not happy paths
- Assume dependencies will degrade, timeout, or lie
- Model systems as **data flow + failure handling**, not just endpoints

---

### current stack

- **Ruby / Rails** for shipping fast and maintaining sanity in production
- **Go** where performance, concurrency, and operational simplicity matter
- **Postgres + Redis** as core primitives, not afterthoughts
- **OpenTelemetry** for tracing real behavior, not guessing
- **AWS + Terraform** for infra that can be reproduced, not "it works on my account"
- **GitHub Actions** for pipelines that don't require human babysitting

---

### on Python

I use it when it's the fastest way to move data, prototype, or test ideas.
I don't build systems around it unless there's a very good reason.

Tools, not identity.

---

### currently

- Shipping Ruby in production environments that actually matter
- Moving critical paths to Go where latency and control become bottlenecks
- Spending time on distributed systems fundamentals instead of chasing frameworks
- Breaking things in controlled environments so they don't break in production

---

### interests (not the cringe kind)

- Distributed systems failure modes
- Event-driven architectures that don't turn into spaghetti
- Observability that tells the truth
- Data pipelines that don't silently rot
- Security + adversarial thinking in real systems

---

### anti-patterns I avoid

- Over-engineering before traffic exists
- Silent retries that hide real issues
- "Magic" abstractions nobody understands
- Systems that only work under ideal conditions
- Chasing tools instead of solving problems

---

### contact

[michaelcaney750@gmail.com](mailto:michaelcaney750@gmail.com)

---

<div align="center">

<img alt="stats" src="https://github-readme-stats.vercel.app/api?username=mcaney006&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" />
<img alt="langs" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mcaney006&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&count_private=true" />

<br/>

<img alt="streak" src="https://streak-stats.demolab.com/?user=mcaney006&theme=tokyonight&hide_border=true" />

<br/>

<img alt="contribution graph" src="https://github-readme-activity-graph.vercel.app/graph?username=mcaney006&theme=tokyo-night&hide_border=true&area=true&custom_title=contribution%20graph&bg_color=1a1b27&color=a9b1d6&line=70a5fd&point=bf91f3" />

</div>
