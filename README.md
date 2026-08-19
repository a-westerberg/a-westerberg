# Hey, I'm Alex 👋

Agile Java Developer, graduated June 2026.

I build and run The Game Cellar, a microservice platform that is live in production on infrastructure I set up myself.

During my internship I worked on Python backend at a startup, shipping real features. My favorite part of development is taking a new feature from idea to working code.

---

## What I work with

```python
languages  = ["Java", "Python", "TypeScript", "SQL"]
frameworks = ["Spring Boot", "FastAPI", "React", "Tailwind"]
databases  = ["PostgreSQL", "MySQL", "MongoDB", "Redis"]
tools      = ["Docker", "Git", "GitHub Actions", "Linux"]
```

---

## The Game Cellar

<a href="https://github.com/The-Game-Cellar">
  <img src="https://raw.githubusercontent.com/The-Game-Cellar/.github/main/docs/hero.png" alt="The Game Cellar"
width="100%" />
</a>

A microservice platform for managing a personal game backlog, with content-based recommendations. Track game status,
rate titles 1–10, and get personalized suggestions based on declared preferences and rating history.

**Stack:** Java 21, Spring Boot 4, PostgreSQL 17, Redis 7, Keycloak 26, React 19, TypeScript, Tailwind, TanStack Query, IGDB API, Docker.

**Architecture:** API Gateway fronting three independent services (Game, Library, Recommendation), each with its own
database. User identity from Keycloak JWT, never request bodies.

**Infrastructure:** Live at [gamecellar.app](https://gamecellar.app) (sign-up opens once email verification lands). CI on GitHub Actions across all five repos via reusable workflows, images published to GHCR, deployed to a self-managed hardened Linux VPS running Docker Compose behind nginx with Let's Encrypt and Cloudflare.

**Repos:** [organization](https://github.com/The-Game-Cellar) ·
[frontend](https://github.com/The-Game-Cellar/frontend) ·
[api-gateway](https://github.com/The-Game-Cellar/api-gateway) ·
[game-service](https://github.com/The-Game-Cellar/game-service) ·
[library-service](https://github.com/The-Game-Cellar/library-service) ·
[recommendation-service](https://github.com/The-Game-Cellar/recommendation-service)

---
 
## Internship – Podmanager.ai
 
Some of what I built there:
 
- **Lead scoring system** – RSS parser that detects which tools a podcast uses and scores them as leads across four tiers
- **Email validation system** – multi-layer validation with a lead state machine, bounce protection and rate limiting
- **Marketplace flow** – claim flow with magic links, profile migration and scheduled nudge chains
- **Email generator** – combines RSS data with a phrase library to write personalized outbound emails
 
All in Python, working independently on GitHub issues in a team of three.
 
---
 
## Contact
 
📍 Timrå, Sweden  
🔗 [LinkedIn](https://www.linkedin.com/in/alexander-westerberg-svedberg-708239314/)
