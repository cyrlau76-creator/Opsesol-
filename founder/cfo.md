# Note du directeur financier — OPSESOL (micro-entreprise)

> Montants en **euros HT** (l'outil affiche « $ » : lire « € »). Unité : **1 jour facturé**, à 600 € (base prudente).
> **1 « jour » de l'outil = 1 mois** : « 1 a day » se lit « 1 jour facturé par mois ». L'outil arrondit le seuil à 1.
> En micro-entreprise, les cotisations (25,6 % + 0,2 %) et l'impôt en versement libératoire (2,2 %) sont des frais
> par jour facturé : le « résultat » ci-dessous est donc **ce qui vous reste en poche**, cotisations et impôt payés.

**La conclusion : en micro-entreprise, chaque jour facturé vous laisse 386 €, et l'année de test environ 1 695 € nets, disponibles au fil de l'eau.**

- **La marge.** Sur 600 € facturés : 46 € de frais directs, 154,80 € de cotisations, 13,20 € d'impôt ⇒ **386 €** (64 %).
- **Le seuil de rentabilité.** Frais fixes : 100 €/mois (pas d'expert-comptable obligatoire) ⇒ **0,26 jour facturé par mois** (100 ÷ 386).
- **L'année de test** (7,5 jours facturés) : **4 500 € de CA, 1 695 € nets**, 845 € après les 850 € de frais de lancement (immatriculation gratuite). Mise de départ remboursée au **mois 10**.
- **La trésorerie à prévoir : 1 050 €** (le creux arrive au mois 2).
- **Comparaison SASU** (même hypothèse) : ~1 080 € nets, et seulement après l'approbation des comptes.

## La ligne à surveiller : le volume

- Volume −20 % : 1 116 € nets sur l'année de test. Coûts unitaires +15 % : 1 454 €.
- **Votre objectif de 3 500 € net/mois** demande (3 500 + 400 de frais fixes à temps plein) ÷ 386 ≈ **10 jours facturés par mois**, soit ~72 700 € de CA par an : sous le plafond de 83 600 €, avec peu de marge.

## Trois façons d'améliorer le résultat (outil, `--volume`)

| Action | Ce qui change | Net année de test |
|---|---|---:|
| Base : 600 €/jour, 7,5 jours | — | 1 695 € |
| Facturer 2 jours par mois dès le début | volume ×2 | **4 590 €** |
| Vendre le Check-up (≈ 800 €/jour de travail) | prix +33 % | plus élevé ; à recalculer avec des cotisations proportionnelles (l'outil ne les ajuste pas avec `--price`) |
| Vérifier le droit au versement libératoire | sinon impôt au barème, sur 66 % du CA, à votre taux marginal | à calculer avec votre avis d'imposition |

## Les conditions financières du conseil

- [x] Plan recalé sur la capacité réelle (5 à 10 jours en année de test) : 7,5 jours.
- [ ] Garantie chiffrée : faite dans `founder/offer.md`, à reprendre en micro.
- [ ] Preuve de demande : aucune vente réelle ; la rampe est une hypothèse.

Hypothèses et sources : `founder/cfo-sources.md`. Ce n'est pas un conseil financier, fiscal ou social : un expert-comptable (consultation ponctuelle) et l'Urssaf doivent confirmer les taux et votre éligibilité au versement libératoire et à l'ACRE.

---

# Unit economics: OPSESOL (micro-entreprise) — Check-up et audits d'exploitation citerne / vrac liquide. Euros HT. 1 « jour » de l'outil = 1 MOIS (days_per_month = 1) : « units a day » se lit « jours facturés par mois ». Cotisations et impôt sont comptés par jour facturé à 600 € : un what-if --price ne les ajuste pas.

Every number below comes from the input file. Nothing is looked up or guessed.

## One jour facturé

| line | per jour facturé |
| --- | ---: |
| Price | $600.00 |
| Déplacement par jour d'intervention (ESTIMATION : ~60 km aller-retour, ~0,60 €/km) | -$36.00 |
| Petits frais par mission (ESTIMATION) | -$10.00 |
| Cotisations sociales micro-entreprise 25,6 % + formation professionnelle 0,2 % du CA (urssaf.fr 2026 ; 0,2 % à vérifier) | -$154.80 |
| Impôt sur le revenu en versement libératoire 2,2 % du CA (si éligible, à vérifier) | -$13.20 |
| **Contribution** (what each jour facturé leaves to pay the fixed costs) | **$386.00** (64%) |

## The margin that matters

Fixed costs: $100 a month (Consultation ponctuelle d'un expert-comptable (ESTIMATION ~300 €/an) $25, Assurance RC pro (ESTIMATION ~300 €/an, devis à obtenir) $25, Compte bancaire dédié (ESTIMATION) $15, Plateforme de facturation électronique (ESTIMATION) $15, Logiciels, téléphone, nom de domaine (ESTIMATION) $20).

- **Break-even: 1 jour facturés a day.** Below that you lose money every month.
- **Profit margin at your plan** (1 a day): **48%** of every sale, after every cost.
- Capacity: 2 a day.

## Year 1, month by month

| month | jour facturés a day | revenue | profit | cumulative (after $850 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 0 | $0 | -$100 | -$950 |
| 2 | 0 | $0 | -$100 | -$1,050 |
| 3 | 0 | $300 | $93 | -$957 |
| 4 | 0 | $300 | $93 | -$864 |
| 5 | 1 | $600 | $286 | -$578 |
| 6 | 0 | $300 | $93 | -$485 |
| 7 | 0 | $0 | -$100 | -$585 |
| 8 | 1 | $600 | $286 | -$299 |
| 9 | 1 | $600 | $286 | -$13 |
| 10 | 1 | $600 | $286 | $273 |
| 11 | 1 | $600 | $286 | $559 |
| 12 | 1 | $600 | $286 | $845 |

- **Year 1 operating profit: $1,695** on $4,500 of revenue.
- After the $850 startup spend: $845.
- Startup money earned back: month 10.
- Cash you need before it pays for itself: **$1,050**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 48% | 1 | $1,695 |
| Price -10% | 42% | 1 | $1,245 |
| Volume -20% | 44% | 1 | $1,116 |
| Unit costs +15% | 42% | 1 | $1,454 |

No red flags in these numbers. They are only as good as the inputs: check every cost against a real quote.
