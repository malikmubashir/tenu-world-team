# Tenu — Financial Projections

> **Statut documentaire — orientation propriétaires du 29 octobre 2026.** Hypothèses/prévisions de l'ancienne offre, à recalculer avec les lots et coûts propriétaires ; aucun chiffre n'est validé pour le nouveau modèle. Source active : [cadre propriétaires](../05-Legal-Compliance/11-Cadre-Proprietaires-Parcours-Location.md), [produit](../02-Product/01-Product-Specification.md), [hypothèses financières](../04-Financial/04-Hypotheses-Proprietaires.md). Le propriétaire particulier est le client ; les anciens ciblages/prix/abonnements ne s'appliquent pas par défaut.


**Version:** 1.0  
**Date:** 2026-04-02

---

## Unit Economics

| Item | Amount |
|---|---|
| Launch price (flat) | €15 / £15 |
| Stripe fee per transaction | €0.46 (1.4% + €0.25) |
| Claude Haiku cost per user | €0.30 |
| Placid PDF cost per user | €0.02 (at scale) |
| Net revenue per user (base) | **€14.22** |
| Dispute add-on price | €20 / £20 |
| Claude Sonnet cost per dispute | €0.60 |
| Net revenue per dispute add-on | **€18.94** |
| Gross margin (base only) | **94.8%** |
| Gross margin (blended 20% dispute) | **88.6%** |

---

## Fixed Monthly Costs

| Tool | Cost |
|---|---|
| Webflow Starter | €14 |
| Make.com Core | €9 |
| Tally Pro | €24 |
| Placid Starter (first 100 users free) | €0–15 |
| **Total fixed** | **€47–62/mo** |

---

## Variable Costs (per 100 users)

| Item | Cost |
|---|---|
| Claude Haiku (risk scoring) | €30 |
| Claude Sonnet (20% dispute rate) | €12 |
| Cloudflare R2 storage | €2 |
| Brevo (within free tier) | €0 |
| **Total variable per 100 users** | **~€44** |

---

## Revenue Scenarios — Year 1

### Bear Case (800 annual users)
| Month | Users | Revenue | Costs | Net |
|---|---|---|---|---|
| Apr–Jun | 30 | €450 | €141 | +€309 |
| Jul–Sep | 250 | €3,750 | €257 | +€3,493 |
| Oct–Dec | 300 | €4,500 | €279 | +€4,221 |
| Jan–Feb | 50 | €750 | €69 | +€681 |
| Mar | 170 | €2,550 | €122 | +€2,428 |
| **Total** | **800** | **~€12,000** | **~€868** | **~€11,132** |

*Note: excludes legal costs (€1,500), accounting, and any founder salary*

### Base Case (2,000 annual users)
| Quarter | Users | Revenue | Costs | Net |
|---|---|---|---|---|
| Q1 (Apr–Jun) | 100 | €1,700 | €191 | +€1,509 |
| Q2 (Jul–Sep) | 700 | €12,600 | €495 | +€12,105 |
| Q3 (Oct–Dec) | 800 | €14,400 | €559 | +€13,841 |
| Q4 (Jan–Mar) | 400 | €7,200 | €335 | +€6,865 |
| **Total** | **2,000** | **~€35,900** | **~€1,580** | **~€34,320** |

### Bull Case (4,500 annual users)
| Quarter | Users | Revenue | Costs | Net |
|---|---|---|---|---|
| Q1 | 200 | €3,800 | €238 | +€3,562 |
| Q2 | 1,500 | €28,500 | €963 | +€27,537 |
| Q3 | 1,800 | €34,200 | €1,099 | +€33,101 |
| Q4 | 1,000 | €19,000 | €679 | +€18,321 |
| **Total** | **4,500** | **~€85,500** | **~€2,979** | **~€82,521** |

*Bull case assumes 20% dispute upsell rate and room-based pricing from month 4*

---

## Breakeven Analysis

| Metric | Value |
|---|---|
| Fixed monthly cost | €47 |
| Net per user | €14.22 |
| Users to break even | **4 users/month** |
| Revenue at breakeven | €56.88 |
| Days to first breakeven (base) | **~Month 1** |

---

## 3-Year Revenue Outlook

| Year | Users | Avg Transaction | Revenue | Notes |
|---|---|---|---|---|
| Year 1 | 2,000 | €18 | ~€36,000 | Launch pricing, no success fee |
| Year 2 | 8,000 | €24 | ~€192,000 | Room pricing + dispute upsell + B2B starts |
| Year 3 | 25,000 | €28 | ~€700,000 | Success fee live, B2B, MuslimPro expansion |

---

## Pricing Transition Plan

| Phase | Period | Pricing |
|---|---|---|
| Launch flat | Months 1–3 | €15 flat all rooms |
| Standard | Month 4+ | €15 + €5/extra room |
| Dispute standard | Month 4+ | €30 (up from €20) |
| Success fee pilot | Month 7+ | 15% of recovered deposit |
| B2B licensing | Month 6+ | TBD — pilot with 1 university |

---

## Cash Reserve Requirement

Build 3-month cash reserve from Global Apex consulting before launch:
- Target: **€3,000–5,000**
- Covers: Jan–Feb dead zone in bear case + legal costs buffer
- Source: Global Apex consulting revenue (ring-fence immediately)

---

*Last updated: 2026-04-02*
