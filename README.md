# Davit Tavadze

Full-stack engineer based in Georgia 🇬🇪. I build production systems — CRMs, VoIP platforms, traffic-replay infrastructure — the kind of software real businesses run their operations on.

**Currently shipping:** [clearvoiance](https://github.com/charlses/clearvoiance) — an open-source traffic capture + replay system that records real production traffic and replays it safely at N× speed, so teams can catch breaking points before they hit production. → [clearvoiance.vercel.app](https://clearvoiance.vercel.app)

---

### What I work on

- **Backend systems** — Node.js, Go, Strapi, gRPC, Postgres, ClickHouse
- **Frontend** — Next.js, React, TypeScript, Tailwind
- **Real-time infra** — WebRTC / SIP.js for VoIP, Socket.io for live dashboards
- **Developer tooling** — SDKs, OSS libraries, internal platforms
- **Ops** — Docker Swarm, Traefik, self-hosted everything

### What I'm currently working on

**[clearvoiance](https://github.com/charlses/clearvoiance)** is taking up most of my time these days. Four parts, one repo:

- **Go engine** — gRPC + REST + WebSocket control plane, ClickHouse + MinIO + Postgres for storage
- **[@clearvoiance/node](https://www.npmjs.com/package/@clearvoiance/node)** — the Node SDK, with adapters for Express, Koa, Fastify, Strapi, Socket.io, BullMQ, node-cron, Knex, Prisma, and Mongoose
- **Next.js dashboard** — live session views, replay progress, DB-observation drill-down, monitors for remote-controlled capture
- **DB observer** — out-of-process binary that joins slow queries back to the exact request that caused them

Day-to-day I'm shipping protos → engine → SDK → UI → docs in small increments, making the whole thing usable for people outside my own stack.

### Tech I reach for

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Strapi](https://img.shields.io/badge/-Strapi-4945FF?style=flat-square&logo=strapi&logoColor=white)
![Fastify](https://img.shields.io/badge/-Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![gRPC](https://img.shields.io/badge/-gRPC-244C5A?style=flat-square&logo=grpc&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/-ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Traefik](https://img.shields.io/badge/-Traefik-24A1C1?style=flat-square&logo=traefikproxy&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

---

### GitHub stats

<table>
  <tr>
    <td valign="top">
      <img alt="Davit's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=charlses&show_icons=true&count_private=true&hide_border=true&theme=tokyonight&rank_icon=github" />
    </td>
    <td valign="top">
      <img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=charlses&layout=compact&hide_border=true&theme=tokyonight&langs_count=8" />
    </td>
  </tr>
</table>

<p>
  <img alt="GitHub streak" src="https://streak-stats.demolab.com/?user=charlses&hide_border=true&theme=tokyonight" />
</p>

<p align="center">
  <img alt="Trophies" src="https://github-profile-trophy.vercel.app/?username=charlses&theme=tokyonight&no-bg=true&no-frame=true&row=1&column=6" />
</p>

<p>
  <img alt="Profile views" src="https://komarev.com/ghpvc/?username=charlses&style=flat-square&color=7aa2f7&label=Profile+views" />
</p>

---

### How I work

Small, shippable increments. Production-first thinking — if it doesn't survive real traffic, it doesn't count. I like owning a feature end-to-end: proto schema → backend → SDK → UI → docs.

### Contact

- **Website** — [charlses.com](https://charlses.com)
- **LinkedIn** — [linkedin.com/in/davit-tavadze](https://www.linkedin.com/in/davit-tavadze/)
- **Email** — [davit.tavadzee@gmail.com](mailto:davit.tavadzee@gmail.com)

<sub>Open to collaboration on OSS — especially around developer tooling, replay/testing systems, or anything performance-sensitive.</sub>
