<div align="center">

<a href="#">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1220,50:1a365d,100:2563eb&height=220&section=header&text=Michael%20Caney%20Jr&fontColor=ffffff&fontSize=54&fontAlignY=38&desc=Freight%20Intelligence%20%E2%80%A2%20Identity%20Systems%20%E2%80%A2%20OSINT&descAlignY=62&descSize=16&animation=fadeIn" alt="Profile banner" />
</a>

<br/>

<p>
  <strong>Engineer working at the intersection of freight, identity, and fraud defense.</strong><br/>
  Rails · Postgres · Sidekiq Pro · OpenTelemetry · Okta SCIM 2.0 · a little Python when it has to be.
</p>

<br/>

<p>
  <a href="https://github.com/mcaney006?tab=repositories"><img alt="Repos" src="https://img.shields.io/badge/repos-explore-1a365d?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="mailto:michaelcaney750@gmail.com"><img alt="Email" src="https://img.shields.io/badge/email-contact-c73028?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://github.com/mcaney006/caneyjrs_-highway_monitor"><img alt="Highway Monitor" src="https://img.shields.io/badge/current_focus-Highway_Monitor-2563eb?style=for-the-badge&logo=ruby&logoColor=white"></a>
</p>

</div>

---

**Stack:** Rails 7.2 · Ruby 3.3 · PostgreSQL + TimescaleDB · Sidekiq Pro · Redis · OpenSearch · S3 · OpenTelemetry · Yabeda/Prometheus · Okta SCIM 2.0

```
┌─── ingest ────┐    ┌─── decide ──────┐    ┌─── act ─────┐
│ FMCSA · TMS   │───▶│ Rule engine     │───▶│ Block / warn│
│ Broker portal │    │ Identity fusion │    │ Notify      │
└───────────────┘    └─────────────────┘    └─────────────┘
```

---

## 🔎 What else I do

**Threat intelligence & OSINT** — I run investigation cases through a personal
platform called **NEXUS** covering phishing kit takedowns, fraud rings, and
identity-laundering schemes. Currently tracking five active cases, including a
Russian AiTM phishing kit targeting freight broker onboarding.

**Secure-by-default engineering** — every repo I maintain runs:
- `CodeQL` (security-extended + security-and-quality queries)
- `gitleaks` (PR + weekly full-history)
- `secure_headers` (HSTS preload, CSP, XFO, Referrer-Policy)
- `Brakeman` (Rails SAST)
- Dependabot with grouping rules + auto-security-fixes
- Signed commits + branch protection with required status checks

---

## 📚 Stack I reach for

<p align="center">
  <img alt="Rails"      src="https://img.shields.io/badge/Rails-CC0000?style=flat-square&logo=rubyonrails&logoColor=white">
  <img alt="Ruby"       src="https://img.shields.io/badge/Ruby-701516?style=flat-square&logo=ruby&logoColor=white">
  <img alt="Postgres"   src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Timescale"  src="https://img.shields.io/badge/TimescaleDB-FDB515?style=flat-square&logo=timescale&logoColor=black">
  <img alt="Redis"      src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white">
  <img alt="Sidekiq"    src="https://img.shields.io/badge/Sidekiq%20Pro-B1003E?style=flat-square&logo=sidekiq&logoColor=white">
  <img alt="Docker"     src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img alt="OTel"       src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white">
  <img alt="Prometheus" src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white">
  <img alt="AWS"        src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
  <img alt="Terraform"  src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white">
  <img alt="Okta"       src="https://img.shields.io/badge/Okta_SCIM-007DC1?style=flat-square&logo=okta&logoColor=white">
</p>

---

## 📈 GitHub activity

<p align="center">
  <img alt="Contribution graph" src="https://github-readme-stats.vercel.app/api?username=mcaney006&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0b1220&title_color=60a5fa&icon_color=60a5fa&text_color=e5e7eb" />
  &nbsp;
  <img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mcaney006&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0b1220&title_color=60a5fa&text_color=e5e7eb" />
</p>

---

## 🧭 Guiding principles

1. **Fail loud, not silent.** A system that can't evaluate a rule is a P0, not a soft skip.
2. **Single source of truth per fact.** Data flows out from one canonical record; integrations reconcile against it, not against each other.
3. **Every RPC has a budget.** Retry + circuit-breaker envelopes at the adapter level, not scattered through business logic.
4. **Observability is a product feature.** If the on-call engineer can't diagnose from the dashboard, the shipping work isn't done.

---

<sub>📍 Based in Texas · ✍️ Writing `highway-monitor` in the open · 💬 Always up for conversations about freight, identity, or fraud defense.</sub>
