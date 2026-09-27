<div align="center">

<img src="assets/banner-2026-09.png" alt="yonyon.ai: one engineer, an army of AI agents" width="100%" />

<br/><br/>

### One engineer. An army of AI agents.

I build AI systems that run businesses: agents, automations, knowledge bases, custom AI apps.<br/>
Founder of **[yonyon.ai](https://yonyon.ai)** · creator of **[OrchestKit](https://github.com/yonatangross/orchestkit)**.

<a href="https://yonyon.ai"><img src="https://img.shields.io/badge/yonyon.ai-C8962F?style=for-the-badge&logo=googlechrome&logoColor=221B22&labelColor=221B22&color=C8962F" alt="yonyon.ai" /></a>
<a href="https://www.linkedin.com/in/yonatangross/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://x.com/yonyoniz"><img src="https://img.shields.io/badge/X-221B22?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
<a href="mailto:hi@yonyon.ai"><img src="https://img.shields.io/badge/hi@yonyon.ai-221B22?style=for-the-badge&logo=maildotru&logoColor=C8962F" alt="Email hi@yonyon.ai" /></a>
<a href="https://yonyon.ai/book?utm_source=github&utm_medium=profile"><img src="https://img.shields.io/badge/Book_a_15--min_intro-C8962F?style=for-the-badge&labelColor=221B22&color=C8962F" alt="Book a 15-min intro" /></a>

</div>

---

yonyon.ai is a one-engineer AI studio in Tel Aviv. I design, ship and run the whole system myself, with an army of AI agents doing the work around the clock: multi-agent backends, RAG, infrastructure, CI and full-stack product. Every change is reviewed before it ships.

## OrchestKit: the AI dev toolkit for Claude Code

<div align="center">

<a href="https://github.com/yonatangross/orchestkit"><img src="https://img.shields.io/github/stars/yonatangross/orchestkit?style=for-the-badge&color=C8962F&labelColor=221B22&logo=github&logoColor=C8962F" alt="Stars" /></a>
<a href="https://github.com/yonatangross/orchestkit"><img src="https://img.shields.io/github/package-json/v/yonatangross/orchestkit?style=for-the-badge&label=version&color=C8962F&labelColor=221B22" alt="Version" /></a>
<img src="https://img.shields.io/badge/106-skills-C8962F?style=for-the-badge&labelColor=221B22" alt="106 skills" />
<img src="https://img.shields.io/badge/36-agents-C8962F?style=for-the-badge&labelColor=221B22" alt="36 agents" />
<img src="https://img.shields.io/badge/171-hooks-C8962F?style=for-the-badge&labelColor=221B22" alt="171 hooks" />

</div>

<br/>

> **Stop explaining your stack. Start shipping.** OrchestKit encodes production patterns (backend, frontend, AI/LLM, security, DevOps, testing, product), so Claude Code already knows your architecture before you type a word.

**Claude Code**

```bash
/plugin marketplace add yonatangross/orchestkit
/plugin install ork
```

**Cursor:** Settings → marketplaces → `yonatangross/orchestkit` → enable **ork** → new chat.

**Starter 12 (skills.sh, any agent)**, not the whole catalog:

```bash
npx skills add yonatangross/orchestkit -s doctor -s setup -s explore -s implement -s verify -s review-pr -s commit -s expect -s assess -s brainstorm -s create-pr -s remember
```

The implement skill is [`implement`](https://www.skills.sh/yonatangross/orchestkit/implement), not `ork-implement`.

Coverage spans backend (FastAPI, PostgreSQL, REST/GraphQL), AI/LLM (LangGraph, RAG, evals, prompt engineering), frontend (React 19, Next.js, TypeScript), workflows (PR review, implementation, brainstorming), testing, DevOps (CI/CD, Docker, Terraform), product, and security.

<p align="center"><a href="https://github.com/yonatangross/orchestkit"><b>Repo</b></a> · <a href="https://orchestkit.yonyon.ai"><b>Docs</b></a> · <a href="https://yonyon.ai/compare/orchestkit-superpowers"><b>vs Superpowers</b></a></p>

---

## What I build

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Multi-agent AI platforms</h3>
      <p>Production LangGraph systems: supervisor/worker patterns, RAG over pgvector, real-time WebSocket streaming, and LLM pool failover across providers.</p>
      <p>
        <img src="https://img.shields.io/badge/LangGraph-FF6B6B?style=flat-square" alt="LangGraph" />
        <img src="https://img.shields.io/badge/pgvector-316192?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>AI operations infrastructure</h3>
      <p>End-to-end platforms with custom MCP servers, WhatsApp + comms integration, AI command centers, automated content pipelines, and LLM evaluation harnesses.</p>
      <p>
        <img src="https://img.shields.io/badge/MCP_Servers-7c3aed?style=flat-square" alt="MCP" />
        <img src="https://img.shields.io/badge/Claude_SDK-FF6B35?style=flat-square&logo=anthropic&logoColor=white" alt="Claude SDK" />
        <img src="https://img.shields.io/badge/Langfuse-14b8a6?style=flat-square" alt="Langfuse" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Full-stack product</h3>
      <p>React 19 + Next.js front ends on FastAPI / Node back ends. Clean architecture, optimistic updates, TanStack Query, typed end to end with Zod.</p>
      <p>
        <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React 19" />
        <img src="https://img.shields.io/badge/Next.js-221B22?style=flat-square&logo=next.js&logoColor=white" alt="Next.js" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>Infrastructure & DevOps</h3>
      <p>Terraform-managed infra across Hetzner, Cloudflare, and Vercel. Docker deploys, GitHub Actions CI/CD, and Cloudflare Tunnels for secure ingress.</p>
      <p>
        <img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white" alt="Terraform" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
        <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare" />
      </p>
    </td>
  </tr>
</table>

---

## Stack

<div align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/C%23_.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="C# .NET" />
<br/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/LangGraph-FF6B6B?style=for-the-badge" alt="LangGraph" />
<img src="https://img.shields.io/badge/Claude_SDK-FF6B35?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude SDK" />
<img src="https://img.shields.io/badge/MCP-7c3aed?style=for-the-badge" alt="MCP" />
<img src="https://img.shields.io/badge/pgvector-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="pgvector" />
<br/>
<img src="https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React 19" />
<img src="https://img.shields.io/badge/Next.js-221B22?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
<img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />

</div>

---

<div align="center">

**Want an army of AI agents working for your business?** → **[Book a 15-min intro](https://yonyon.ai/book?utm_source=github&utm_medium=profile)**

</div>
