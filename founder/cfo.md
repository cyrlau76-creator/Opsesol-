# Note du directeur financier — OPSESOL

> Montants en **euros HT** (l'outil affiche « $ » : lire « € »). Unité : **1 jour facturé**. L'outil compte en « par jour » :
> ici **1 « jour » de l'outil = 1 mois**, donc « 1 a day » se lit « 1 jour facturé par mois ». Les arrondis de l'outil
> affichent « 1 » là où le calcul exact donne moins (voir le seuil ci-dessous). TVA en sus selon le régime choisi.

**La conclusion : OPSESOL ne perd pas d'argent, mais ne peut pas atteindre votre objectif de revenu tant que vous êtes salarié à temps plein.**

- **La marge.** Chaque jour facturé à 600 € laisse **554 €** après ses frais directs (92 %). À 1 jour par mois, la marge nette après tous les frais fixes est de **60 %**.
- **Le seuil de rentabilité.** Frais fixes : 195 €/mois, soit **0,35 jour facturé par mois** (195 ÷ 554). Le risque financier est quasi nul.
- **L'année 1** (7,5 jours facturés au total, de 0 à 1 jour par mois) : **4 500 € de CA, 1 815 € de résultat d'exploitation, 275 € après les frais de création** (1 540 €). La mise de départ est remboursée au mois 12.
- **La trésorerie à prévoir : 1 930 €** avant que l'activité se finance seule (le creux arrive au mois 2).
- **Ce qui vous revient.** Président non rémunéré, résultat versé en dividendes : IS 15 % puis prélèvement forfaitaire ~30 % (taux à vérifier) ⇒ environ **59,5 %** du résultat. Année 1 : 1 815 × 0,85 × 0,70 ≈ **1 080 € net sur l'année, soit ~90 €/mois.**

## La ligne à surveiller : le volume, pas les coûts

- Volume −20 % : résultat année 1 **984 €** et frais de création **pas remboursés** dans l'année.
- Coûts unitaires +15 % : 1 763 € (presque rien ne bouge). Vos frais sont trop faibles pour être le levier.
- **Votre objectif de 3 500 € net/mois** demande ~5 880 € de résultat par mois (3 500 ÷ 0,595), soit **~11 jours facturés par mois** ((5 880 + 195) ÷ 554). Votre capacité actuelle est d'environ **2 jours par mois** (16 h). L'écart est un facteur 5 : il ne se comble ni par le prix ni par les coûts, seulement par le temps disponible.

## Trois façons d'améliorer le résultat (calculées avec l'outil)

| Action | Ce qui change | Résultat d'exploitation année 1 |
|---|---|---:|
| Base : 600 €/jour, 7,5 jours | — | 1 815 € |
| Passer le prix moyen à **700 €/jour** (diagnostic à prix fixe) | +100 €/jour | **2 565 €** (+750 €) |
| Passer le prix moyen à **800 €/jour** | +200 €/jour | **3 315 €** (+1 500 €) |
| Facturer **2 jours par mois** dès le début (capacité maximale) | volume ×2 | **5 970 €** (+4 155 €) |

Point de cohérence de votre grille : **l'audit complet à 1 800 € pour 5 jours revient à 360 €/jour**, sous votre plancher de 500 €. À 600 €/jour, le minimum est 3 000 € ; un forfait de 3 000 à 3 500 € est cohérent.

## Les conditions financières du conseil

- [x] **Plan recalé sur la capacité réelle (5 à 10 jours en année 1)** : fait, 7,5 jours.
- [ ] **Une garantie que le budget peut supporter** : à chiffrer avec `/founder-offer`.
- [ ] **Preuve de demande** : aucune vente réelle encore ; la rampe ci-dessous est une hypothèse, pas une mesure.

Tous les frais fixes et les frais de création sont des **estimations** (détail : `founder/cfo-sources.md`). Un expert-comptable doit valider la structure, la fiscalité des dividendes et le régime de TVA avant tout engagement. Ceci n'est pas un conseil financier, fiscal ou juridique.

---

# Unit economics: OPSESOL (SASU) — diagnostic et audit d'exploitation citerne / vrac liquide. Montants en euros HT. Ici, 1 « jour » du rapport = 1 MOIS : days_per_month = 1, donc « units a day » se lit « jours facturés par mois ».

Every number below comes from the input file. Nothing is looked up or guessed.

## One jour facturé

| line | per jour facturé |
| --- | ---: |
| Price | $600.00 |
| Déplacement par jour d'intervention (ESTIMATION : ~60 km aller-retour, barème kilométrique ~0,60 €/km) | -$36.00 |
| Petits frais par mission (impression, repas) (ESTIMATION) | -$10.00 |
| **Contribution** (what each jour facturé leaves to pay the fixed costs) | **$554.00** (92%) |

## The margin that matters

Fixed costs: $195 a month (Expert-comptable SASU (ESTIMATION, devis à obtenir) $120, Assurance RC pro (ESTIMATION ~300 €/an, devis à obtenir) $25, Banque pro (ESTIMATION) $15, Plateforme de facturation électronique (ESTIMATION) $15, Logiciels, téléphone, nom de domaine (ESTIMATION, business plan : 150-250 €/an + téléphone) $20).

- **Break-even: 1 jour facturés a day.** Below that you lose money every month.
- **Profit margin at your plan** (1 a day): **60%** of every sale, after every cost.
- Capacity: 2 a day.

## Year 1, month by month

| month | jour facturés a day | revenue | profit | cumulative (after $1,540 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 0 | $0 | -$195 | -$1,735 |
| 2 | 0 | $0 | -$195 | -$1,930 |
| 3 | 0 | $300 | $82 | -$1,848 |
| 4 | 0 | $300 | $82 | -$1,766 |
| 5 | 1 | $600 | $359 | -$1,407 |
| 6 | 0 | $300 | $82 | -$1,325 |
| 7 | 0 | $0 | -$195 | -$1,520 |
| 8 | 1 | $600 | $359 | -$1,161 |
| 9 | 1 | $600 | $359 | -$802 |
| 10 | 1 | $600 | $359 | -$443 |
| 11 | 1 | $600 | $359 | -$84 |
| 12 | 1 | $600 | $359 | $275 |

- **Year 1 operating profit: $1,815** on $4,500 of revenue.
- After the $1,540 startup spend: $275.
- Startup money earned back: month 12.
- Cash you need before it pays for itself: **$1,930**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 60% | 1 | $1,815 |
| Price -10% | 55% | 1 | $1,365 |
| Volume -20% | 52% | 1 | $984 |
| Unit costs +15% | 59% | 1 | $1,763 |

No red flags in these numbers. They are only as good as the inputs: check every cost against a real quote.
