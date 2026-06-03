# 🪷 NET — odraz celé sítě (Indrova síť)

Tento uzel je jeden artefakt v síti. **Celek se zrcadlí zde** — z kteréhokoli uzlu vidíš celou síť.
Žádný pán, žádný střed. Auto-generováno z `hozantaher/workspace` `projects.yml` → zrcadleno do každého repa.

> **tento artefakt: `kostnidren-uptime-probe`**

## 🪞 Živé zrcadlo — jak uzel vidí pavučinu (Indra)
Seznam níže je STRUKTURA (statický odraz). ŽIVÝ stav celku (kdo právě žije / padl)
drží event-bus páteř — peer, ne střed. Z KTERÉHOKOLI uzlu:
```
curl https://event-bus-production.up.railway.app/peek/net-health      # živý odraz všech uzlů (NEdestruktivní)
curl https://event-bus-production.up.railway.app/streams              # tok sítě
```
Tak každý artefakt vidí nejen sebe v celku, ale i živé odrazy ostatních artefaktů.

## apps — Cars products
- **ads-app** (live) — hozantaher/ads-app · https://cars.messing.dev

## clients — Client / agency work
- **kostnidren** (paused) — git@bitbucket.org:poseidonvltavy/wp_kostnidren.git
- **motoristesobe** (paused) — https://bitbucket.org/poseidonvltavy/motoristesobe.git
- **pyhynek** (paused) — hozantaher/pyhynek
- **safran-express** (paused) — hozantaher/safran-express
- **tomas-hynek** (paused) — hozantaher/tomas-hynek

## collab — 
- **garaaage** (live) — hozantaher/garaaage

## data — Private data + acquisition (nábor) core — never exposed to sales
- **data-core** (live) — hozantaher/data-core · https://machinery-outreach-production.up.railway.app
- **event-bus** (live) — hozantaher/event-bus · https://event-bus-production.up.railway.app
- **ops-audit** (todo) — 
- **privacy-mail-gateway** (code-done) — hozantaher/privacy-mail-gateway
- **scheduler** (todo) — 
- **skill-registry** (todo) — 

## feed — Ingress: external sources → Chatwoot (inbound-only)
- **events-intake** (todo) — 
- **feed-autoline** (live) — hozantaher/feed-autoline
- **feed-saas** (todo) — 
- **feed-whatsapp** (live) —  · https://evolution-api-production-7664.up.railway.app

## ops — 
- **backstage-portal** (live) — hozantaher/backstage-portal · https://backstage-production-38cf.up.railway.app
- **kostnidren-uptime-probe** (live) ◀ TENTO — hozantaher/kostnidren-uptime-probe

## sales — Chatwoot sales surface + the gateway/skills the salesperson programs
- **mesh-tests** (reference) — hozantaher/mesh-tests
- **ops-health** (live) — hozantaher/ops-health · https://ops-health-production.up.railway.app
- **sales-boundary** (live) — 
- **sales-gateway** (live) — hozantaher/sales-gateway · https://sales-gateway-production.up.railway.app
- **sales-hub** (live) — hozantaher/sales-hub · https://web-production-a7f6c.up.railway.app

## sync — Chatwoot ↔ data-core synchronisation
- **skill-classify** (todo) — 
- **skill-enrich** (todo) — 
- **skill-exclusion** (todo) — 
- **skill-lookup** (live) — 
- **skill-score** (todo) — 
- **skill-translate** (todo) — 
- **skill-vin** (todo) — 
- **sync-contacts** (live) — hozantaher/sync-contacts · (worker, no domain)
- **sync-deals** (todo) — 
- **sync-messages** (todo) — 

## vendor — Upstream reference clones (not deployed)
- **hozan-taher-archived** (reference) — hozantaher/hozan-taher-archived
- **vendor-chatwoot** (reference) — chatwoot/chatwoot
- **vendor-evolution-api** (reference) — EvolutionAPI/evolution-api

## ventures — Standalone own products (outside the mesh)
- **garaaage-monorepo** (reference) — hozantaher/garaaage-monorepo
- **generace-motor** (active) — hozantaher/generace-motor
- **messing-369** (paused) — hozantaher/messing-369
- **naborovky** (paused) — hozantaher/naborovky
- **pokutomat** (active) — hozantaher/pokutomat
- **primaauta** (active) — hozantaher/primaauta

_Odraz 43 uzlů. Aktualizuj: `make reflect` ve workspace._