# Hi there, I'm Provant 👋

[![Website](https://img.shields.io/badge/Website-provant.dev-blue?style=flat-square&logo=google-chrome)](https://provant.dev)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github)](https://github.com/provant15)
[![Email](https://img.shields.io/badge/Email-me@provant.dev-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:me@provant.dev)

## About Me

Full-stack developer and infrastructure enthusiast who builds things end-to-end - from network segmentation and server architecture to game servers and web applications. By day, I'm a qualified train driver. By night, I'm building game worlds, tinkering with enterprise-grade homelab infrastructure, and writing code.

I specialise in TypeScript/JavaScript ecosystems with a focus on scalable, secure, and well-architected solutions. Currently working with Bun, React, Supabase, and Cloudflare's platform for web projects, and Java for Minecraft plugin development.

## Currently Working On

- **Pixadom** - A cozy 2D social pixel art MMORPG (Purely community management and consultation)
- **OdysseyCraft** - A comprehensive Minecraft server network with custom plugins and Paper-native architecture
- **Homelab Infrastructure** - Norse themed server cluster with enterprise networking, monitoring, and automation

## Tech Stack

### Languages

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Backend & Runtime

![Bun](https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

### Databases & Caching

![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

### Cloud & Deployment

![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### Infrastructure & Networking

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubiquiti](https://img.shields.io/badge/Ubiquiti-0559C9?style=for-the-badge&logo=ubiquiti&logoColor=white)
![Home Assistant](https://img.shields.io/badge/Home_Assistant-41BDF5?style=for-the-badge&logo=home-assistant&logoColor=white)

### Tools

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

## Homelab - The Nine Realms

A Norse mythology-themed homelab with enterprise-grade UniFi networking, VLAN segmentation across five realms, and dedicated servers for applications, databases, game hosting, and development.

```mermaid
graph TD
    classDef power fill:#b91c1c,stroke:#ef4444,color:#fff,stroke-width:2px
    classDef isp fill:#4a1a6b,stroke:#7c3aed,color:#fff,stroke-width:2px
    classDef gateway fill:#1e3a5f,stroke:#3b82f6,color:#fff,stroke-width:2px
    classDef switch fill:#1a4731,stroke:#10b981,color:#fff,stroke-width:2px
    classDef server fill:#92400e,stroke:#f59e0b,color:#fff,stroke-width:2px
    classDef ap fill:#0e4a6e,stroke:#06b6d4,color:#fff,stroke-width:2px
    classDef endpoint fill:#374151,stroke:#9ca3af,color:#fff,stroke-width:2px
    classDef pi fill:#831843,stroke:#ec4899,color:#fff,stroke-width:2px
    THOR["Thor - UPS"]:::power
    NEPTUNE["Neptune - Internet"]:::isp
    YGGDRASIL["Yggdrasil - UCG Fiber / Gateway"]:::gateway
    HEIMDALL["Heimdall - USW Aggregation / Core Switch"]:::gateway
    ASBRU["Asbru - USW Pro Max 16 / Server Switch"]:::switch
    BIFROST["Bifrost - USW Pro XG 10 PoE / Endpoint Switch"]:::switch
    LOKI["Loki - App Server"]:::server
    MIMIR["Mimir - Database Server"]:::server
    RAGNAR["Ragnar - Game Server 1"]:::server
    SIGURD["Sigurd - Game Server 2"]:::server
    ODIN["Odin - U7 Pro Max / Primary AP"]:::ap
    VE["Ve - Code Server / i9-13900HK 32GB DDR5"]:::server
    ULLR["Ullr - Raspberry Pi 5 / Monitoring"]:::pi
    VOLLUNDR["Vollundr - Raspberry Pi 5 / Home Assistant"]:::pi
    GJALLARBRU["Gjallarbru - USW Flex 2.5G 5"]:::switch
    SVERDRU["Sverdbru - USW Flex 2.5G 5"]:::switch
    MUNINN["Muninn - U6 Mesh / AP"]:::ap
    HUGINN["Huginn - U7 Pro Max / AP"]:::ap
    MAINPC["Main PC"]:::endpoint
    SECPC["Secondary PC"]:::endpoint
    SONOS["Sonos Peripherals"]:::endpoint
    THOR --- NEPTUNE
    NEPTUNE -->|WAN| YGGDRASIL
    YGGDRASIL --> HEIMDALL
    HEIMDALL --> ASBRU
    HEIMDALL --> BIFROST
    ASBRU --> LOKI
    ASBRU --> MIMIR
    ASBRU --> RAGNAR
    ASBRU --> SIGURD
    BIFROST --> ODIN
    BIFROST --> VE
    BIFROST --> ULLR
    BIFROST --> VOLLUNDR
    BIFROST --> GJALLARBRU
    ODIN --> SVERDRU
    ODIN --> MUNINN
    SVERDRU --> HUGINN
    GJALLARBRU --> MAINPC
    GJALLARBRU --> SECPC
    GJALLARBRU --> SONOS
```

> **VLAN Segmentation:** Traffic is isolated across five realms - **Asgard** (trusted devices), **Midgard** (guest network), **Jötunheim** (public-facing services), **Svartalfheim** (IoT & isolated devices), and **Alfheim** (kids & monitored devices).

## GitHub Stats

![GitHub Stats](./profile/stats.svg)
![Top Languages](./profile/top-langs.svg)

## How to Reach Me

- Website: [provant.dev](https://provant.dev)
- Email: [me@provant.dev](mailto:me@provant.dev)

---
