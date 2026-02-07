# Hackathons 2026 — Roadmap Completo

**Proyecto:** Lightning Hackathon Mensual de La Crypta  
**Duración:** 8 meses (Marzo - Octubre 2026)  
**Formato:** Hackathon mensual de 48 horas, jurado 100% AI

---

## Visión del programa

**Progresión educativa de 8 meses** donde cada hackathon profundiza en una temática específica, construyendo sobre lo aprendido en los meses anteriores. Al final del programa, los participantes habrán construido un portafolio completo de herramientas Lightning + Nostr + AI.

**Filosofía:** Aprender construyendo. Cada mes, un focus específico. Los proyectos ganadores se integran al stack de La Crypta.

---

## Roadmap: 8 Hackathons

### Mes 1 — Marzo 2026: FOUNDATIONS ⚡
**Tema:** Lightning Payments Basics  
**Focus:** Invoices, pagos, wallets básicas

**Challenges:**
- Simple Lightning wallet (send/receive)
- Invoice generator con QR codes
- Lightning tip jar para creators
- Payment link generator (hodl.ar style)
- Lightning paywall para contenido

**Stack:** LND, LNURL, webln, QR codes

**Learning goals:**
- Cómo funciona Lightning
- BOLT-11 invoices
- Channels básicos
- Mainnet vs testnet

**Output esperado:** Herramientas básicas de pago que cualquiera puede usar

---

### Mes 2 — Abril 2026: IDENTITY 🔐
**Tema:** Nostr Identity & Social  
**Focus:** Perfiles, autenticación, social básico

**Challenges:**
- Nostr profile manager
- NIP-07 login component
- Simple social feed
- Follow/unfollow system
- Badge displayer (NIP-58)

**Stack:** Nostr-tools, NDK, NIP-07, NIP-05

**Learning goals:**
- Cómo funciona Nostr
- Keys y identity
- Relays
- Eventos básicos (kind 0, 1, 3)

**Builds sobre:** Mes 1 — ahora podés vincular pagos con identidad Nostr

---

### Mes 3 — Mayo 2026: ZAPS ⚡💜
**Tema:** Nostr Zaps (NIP-57)  
**Focus:** Integración Lightning + Nostr

**Challenges:**
- Zap button component
- Zap leaderboard
- Zap-gated content
- Zap splits (multiple recipients)
- Zap analytics dashboard

**Stack:** NIP-57, LNURL-pay, Lightning addresses, NDK

**Learning goals:**
- Cómo funcionan los zaps
- Lightning addresses
- Nostr Wallet Connect (NWC)
- Value-for-value model

**Builds sobre:** Mes 1 + 2 — unificás pagos con social

---

### Mes 4 — Junio 2026: COMMERCE 🛒
**Tema:** Lightning Commerce  
**Focus:** Tiendas, productos, checkout

**Challenges:**
- Simple Lightning store
- Product catalog con Lightning checkout
- Subscription service (recurring payments)
- Donation platform
- E-commerce plugin (WooCommerce/Shopify)

**Stack:** LND, BTCPay Server, Lightning addresses, webhooks

**Learning goals:**
- Lightning para comercio
- Webhooks y confirmations
- Inventory management
- Recurring payments

**Builds sobre:** Mes 1-3 — ahora podés vender productos con Lightning + identidad Nostr

---

### Mes 5 — Julio 2026: MEDIA 📸
**Tema:** Decentralized Media Storage  
**Focus:** Blossom, CDN, hosting

**Challenges:**
- Blossom uploader
- Image/video hosting con Lightning payments
- CDN descentralizado
- Media gallery con Nostr metadata
- Content monetization platform

**Stack:** Blossom, IPFS, Lightning payments, Nostr events

**Learning goals:**
- Almacenamiento descentralizado
- Pay-per-upload models
- CDN economics
- Media metadata en Nostr

**Builds sobre:** Mes 1-4 — ahora tu commerce puede tener media descentralizada

---

### Mes 6 — Agosto 2026: AI AGENTS 🤖
**Tema:** AI Agents + Automation  
**Focus:** Bots, workflows, automation

**Challenges:**
- Nostr bot que responde menciones
- Lightning payment bot
- Auto-zapper (zaps automáticos según criterios)
- Content moderator bot
- AI assistant con Lightning payments

**Stack:** OpenClaw, Claude, LLMs, Nostr, Lightning API

**Learning goals:**
- Agentes autónomos
- API integration
- Workflow automation
- AI + Bitcoin

**Builds sobre:** Mes 1-5 — ahora tus apps tienen automatización inteligente

---

### Mes 7 — Septiembre 2026: INFRASTRUCTURE 🏗️
**Tema:** Nodes, Routing, Liquidity  
**Focus:** Infraestructura Lightning

**Challenges:**
- Node dashboard
- Channel management tool
- Liquidity marketplace
- Routing fee optimizer
- Lightning network explorer

**Stack:** LND/CLN, Graph API, Channel management, Routing algorithms

**Learning goals:**
- Cómo funcionan los nodos
- Channel liquidity
- Routing fees
- Network topology

**Builds sobre:** Mes 1-6 — ahora entendés la infraestructura detrás de todo

---

### Mes 8 — Octubre 2026: INTEGRATION 🌐
**Tema:** Full-Stack Integration  
**Focus:** Proyectos completos end-to-end

**Challenges:**
- App completa que use todo lo anterior:
  - Lightning payments
  - Nostr identity
  - Zaps
  - Commerce
  - Media storage
  - AI agents
  - Node infrastructure

**Ejemplos:**
- Social marketplace con Lightning
- Creator platform con subscriptions
- Community app con pagos integrados
- AI-powered Lightning service

**Stack:** Todo lo de los 7 meses anteriores

**Learning goals:**
- Integración full-stack
- Production deployment
- Scaling considerations
- Real-world launch

**Builds sobre:** Todo — este es el proyecto final

---

## Estructura de cada hackathon

### Timeline
- **Martes 1 del mes (10 AM):** Anuncio + challenges publicados
- **Viernes 3 (6 PM):** Kickoff oficial, formación de equipos
- **Sábado 4:** Desarrollo todo el día
- **Domingo 5 (6 PM):** Deadline de entrega
- **Domingo 5 (7-9 PM):** Demo day
- **Lunes 6:** Evaluación del jurado AI
- **Martes 7:** Anuncio de ganadores + premios

### Premios (por mes)
- **1er lugar:** 1,000,000 sats
- **2do lugar:** 500,000 sats
- **3er lugar:** 250,000 sats
- **Mentions:** 50,000 sats cada una (hasta 3)

**Total por hackathon:** ~2M sats (~$1,200 USD a precio actual)

### Recursos provistos
- Boilerplate actualizado cada mes según temática
- Tutoriales y docs específicos
- Mentores disponibles (Discord)
- Nodos Lightning testnet
- Relays Nostr dedicados
- API keys para servicios necesarios

---

## Progresión de dificultad

| Mes | Dificultad | Focus | Output |
|-----|------------|-------|--------|
| 1 | ⭐ Beginner | Lightning basics | Simple payment tools |
| 2 | ⭐ Beginner | Nostr basics | Identity & social |
| 3 | ⭐⭐ Intermediate | Lightning + Nostr | Zaps integration |
| 4 | ⭐⭐ Intermediate | Commerce | Stores & checkout |
| 5 | ⭐⭐⭐ Advanced | Media storage | Decentralized CDN |
| 6 | ⭐⭐⭐ Advanced | AI automation | Bots & agents |
| 7 | ⭐⭐⭐⭐ Expert | Infrastructure | Node management |
| 8 | ⭐⭐⭐⭐ Expert | Full integration | Production apps |

---

## KPIs del programa

### Por hackathon
- Participantes registrados
- Equipos formados
- Proyectos entregados
- Proyectos que continúan desarrollo post-hackathon

### Programa completo (8 meses)
- **Participantes únicos:** Objetivo 200+
- **Proyectos totales:** Objetivo 100+
- **Proyectos integrados a La Crypta:** Objetivo 20+
- **Contributors activos al ecosistema:** Objetivo 50+
- **Alumni que lanzan startups:** Objetivo 10+

### Métricas de aprendizaje
- % de participantes que completan 3+ hackathons
- % de participantes que avanzan a hackathons más difíciles
- Calidad de código (medida por jurado AI)
- Engagement post-hackathon

---

## Budget total (8 meses)

**Premios:** 16M sats (~$9,600 USD)  
**Infraestructura:** ~$2,000 USD (hosting, APIs, servicios)  
**Marketing:** ~$1,000 USD (diseño, ads, merch)  
**Logística:** ~$2,000 USD (comida, espacio, equipamiento)

**Total:** ~$15,000 USD para el programa completo

---

## Sponsors potenciales

- **OpenSats** — grants para proyectos destacados
- **Strike / River** — servicios Lightning
- **Voltage / Amboss** — infraestructura
- **Alby** — NWC y wallets
- **Hardware wallets** (Coldcard, SeedSigner, Foundation)
- **Exchanges argentinos** (Ripio, Lemon, Buenbit)

---

## Alumni program

Los participantes que completan 5+ hackathons reciben:
- **Badge de Alumni** (Nostr badge + NFT)
- **Acceso prioritario** a futuras ediciones
- **Descuentos en servicios** de La Crypta
- **Networking exclusivo** con el ecosistema
- **Posibilidad de mentorear** en futuros hackathons

---

## Próximos pasos

**Para lanzar el programa:**

1. **Confirmar budget y sponsors** (Enero-Febrero)
2. **Crear landing page** con registro Tally
3. **Desarrollar boilerplate mes 1** (Lightning basics)
4. **Armar kit de comunicación** (logos, templates, copy)
5. **Anuncio público** (3 semanas antes del primer hackathon)
6. **Campaña de difusión** (X, Nostr, Discord, newsletter, podcasts)

**Timeline de lanzamiento:**
- **15 Feb:** Landing live + registro abierto
- **1 Mar (10 AM):** Anuncio oficial primer hackathon
- **6-8 Mar:** Primer hackathon (FOUNDATIONS)

---

**Creado:** 2026-02-07  
**Autor:** Claudio ⚡ (Opus 4.5)  
**Estado:** Roadmap completo — listo para ejecución
