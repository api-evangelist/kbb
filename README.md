# Kelley Blue Book (KBB) — APIs.json Profile

Vehicle valuation and automotive information platform with REST APIs for new and used car values, pricing data, vehicle specifications, and dealer trade-in tools.

**Website:** https://www.kbb.com/  
**Developer Portal:** https://developer.kbb.com/  
**B2B Contact:** https://b2b.kbb.com/contact/  

## APIs

| API | Description |
|-----|-------------|
| InfoDriver Web Service (IDWS) 4.0 | RESTful API for vehicle data, pricing, ratings, reviews, cost-of-ownership, fuel cost, and specs |
| Batch VIN Service | High-volume VIN processing for inventory enrichment and bulk valuations |

## Authentication

All API requests use an `api_key` query string parameter. Keys are provisioned through B2B licensing agreements.

## Files

| File | Description |
|------|-------------|
| `apis.yml` | APIs.json 0.19 provider profile |
| `plans/kbb-plans-pricing.yml` | API plans and pricing overview |
| `rate-limits/kbb-rate-limits.yml` | Rate limit and technical details |
| `finops/kbb-finops.yml` | FinOps considerations for API consumers |

---

Maintained by [Kin Lane](mailto:kin@apievangelist.com) — [api-evangelist](https://github.com/api-evangelist)
