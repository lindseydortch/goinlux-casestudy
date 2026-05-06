# GoinLux
### A Luxury Villa Discovery & Availability Platform

> Making a complex, high touch booking process feel seamless and elevated.

---

## Overview

GoinLux is a luxury villa concierge service that needed a discovery platform for their portfolio of high end rental villas sourced from multiple external providers. The goal was to give users a seamless way to browse, search, and request availability for luxury villas while handling the complexity of a booking process that cannot be instant.

Unlike platforms like Airbnb, GoinLux operates on a concierge model where availability is only updated once a week and every booking request must be manually confirmed with the villa owner directly. The platform needed to communicate that nuance clearly while still delivering a premium, effortless user experience.

---

## The Problem

- Villa data was scattered across 6+ third party APIs, each with their own data structure, update cadence, and quirks
- Availability could not be confirmed instantly due to the nature of the concierge model
- The client needed a way to manage and add their own custom villa listings without touching the codebase
- The platform needed to feel elevated and on brand for a luxury audience while handling significant backend complexity under the hood

---

## My Role

**Founder & Full Stack Engineer, Alors Creative**

I was the sole engineer and technical decision maker on this project, responsible for the full stack architecture, backend engineering, frontend development, and ongoing maintenance.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js |
| CMS | Sanity.io |
| Backend | NestJS + TypeScript |
| ORM | Prisma |
| Database | PostgreSQL |
| APIs | 6+ third party villa data providers + custom GoinLux API |

---

## Architecture & Technical Highlights

### Custom GoinLux API
Rather than forcing villa data through a generic CMS, I built a purpose built GoinLux API that pulls in all villa information from multiple external providers and unifies it into a single coherent data layer. This keeps villa data separate, structured, and purpose built for the platform's specific needs.

### Unified Third Party API Integration
Villa data was sourced from 6+ third party APIs, each with their own structure and update cadence. The backend normalizes all of this data into a consistent format before it ever reaches the frontend, making the experience feel seamless regardless of where the underlying data came from.

### Admin Facing Frontend
To give the client full control over their inventory, I built an admin facing frontend that allows the client to add and manage their own custom villa listings directly without touching the codebase. This makes the platform self sufficient and easy to maintain long term.

### Availability Search
Users can search and filter villas based on current availability, with the platform clearly communicating the weekly update cadence and request based confirmation process so expectations are set upfront.

### Sanity.io CMS
All website content outside of the villa data is managed through Sanity.io, giving the client full control over their marketing content, copy, and media without needing developer involvement.

---

## Key Features

- Villa discovery and search with availability filtering
- Detailed property pages pulling from the unified API layer
- Availability request flow that routes directly to the GoinLux team for confirmation
- Admin portal for the client to add and manage custom villa listings
- Sanity.io powered CMS for all website content management

---

## Outcome

The result is a platform that makes a complex, high touch booking process feel seamless and elevated. For a luxury brand where the experience is everything, the engineering had to be invisible and the product had to feel premium end to end.

---

## Live Site

[Visit GoinLux](#) *(https://goinlux.com/)*

---

*Built by Lindsey Dortch, Alors Creative*
*[lindseydortch.dev](https://lindseydortch.dev) · [linkedin.com/in/lindseydortch](https://linkedin.com/in/lindseydortch) · [github.com/lindseydortch](https://github.com/lindseydortch)*
