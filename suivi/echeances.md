# Calendrier des obligations

> Maintenu par l'agent `comptable-fiscal` (commande `/echeances`). Mise à jour : 28/10/2026.
> Situation : **micro-entreprise** (entreprise individuelle, BNC) à créer, nom commercial OPSESOL,
> début d'activité visé en janvier 2027, activité conseil + formation, entrepreneur salarié en parallèle.
> Le prérequis bloquant (compatibilité avec l'activité salariée) bloque la prospection, pas la création.
> Sources [S…] en bas de fichier. « À vérifier » = non confirmé sur une source officielle.

## 1. Création (ordre conseillé)

| # | Étape | Points d'attention | Source | Statut |
|---|---|---|---|---|
| 1 | Consultation ponctuelle d'un expert-comptable | Valider le régime micro, le versement libératoire et la date de début (questions : `documents/2026/comptabilite/questions-expert-comptable.md`) | — | [ ] |
| 2 | Choisir l'adresse de l'entreprise | Domicile (vérifier bail ou règlement de copropriété, à vérifier) ou domiciliation | — | [ ] |
| 3 | Déclarer le début d'activité sur le guichet unique | https://formalites.entreprises.gouv.fr ; activité libérale non réglementée (BNC), nom commercial OPSESOL ; démarche gratuite (à vérifier au moment du dépôt) | [S10] | [ ] |
| 4 | Dans la déclaration : choisir le versement libératoire (si éligible) et la périodicité des déclarations (mensuelle ou trimestrielle) | Versement libératoire : condition de revenu fiscal à vérifier | [S19] | [ ] |
| 5 | Demander l'ACRE si éligible | Conditions modifiées en 2026 ; probablement pas pour un salarié (à vérifier) | [S20] | [ ] |
| 6 | Recevoir le SIREN ; créer l'espace sur autoentrepreneur.urssaf.fr et l'espace professionnel impots.gouv.fr | — | [S19] | [ ] |
| 7 | Ouvrir un compte bancaire dédié | Recommandé dès le début ; obligatoire si le CA dépasse 10 000 € deux années de suite (à vérifier) | — | [ ] |
| 8 | Souscrire la RC pro | Avant la première mission ; couvrir conseil et formation | — | [ ] |
| 9 | Choisir une plateforme agréée de facturation électronique | Réception obligatoire depuis le 01/09/2026 pour toute entreprise | [S4] [S5] | [ ] |
| 10 | Déclaration initiale de CFE 1447-C-SD | Au plus tard le 31/12 de l'année de création (31/12/2027 si début en 2027) | [S6] [S7] | [ ] |
| 11 | Déclaration d'activité de formation (DREETS) | Seulement si de la formation est facturée : dans les 3 mois suivant la 1re convention (à vérifier) | [S12] | [ ] |
| 12 | Attestation d'exonération de TVA formation (3511-SD) | Uniquement si l'exonération est visée et la déclaration d'activité faite | [S11] | [ ] |

## 2. Calendrier récurrent

### 2.1 Cotisations Urssaf

| Échéance | Obligation | Remarque | Source |
|---|---|---|---|
| Chaque mois ou chaque trimestre (selon le choix) | Déclarer le CA encaissé et payer les cotisations sur autoentrepreneur.urssaf.fr | 25,6 % du CA en 2026 (BNC) + formation professionnelle ~0,2 % (à vérifier) ; déclarer même un CA nul ; dates exactes dans l'espace (à vérifier) | [S19] |
| Même échéance | Versement libératoire de l'impôt, si choisi | ~2,2 % du CA (à vérifier) | [S19] |

### 2.2 Impôt sur le revenu

| Échéance | Obligation | Remarque | Source |
|---|---|---|---|
| Mai-juin (déclaration annuelle des revenus) | Déclarer le CA de l'année sur la 2042-C-PRO | Même avec le versement libératoire. Sans lui : imposition au barème après abattement de 34 % (à vérifier), avec le salaire | [S15] |

### 2.3 TVA

| Situation | Règle | Mentions facture | Source |
|---|---|---|---|
| CA de l'année précédente ≤ 37 500 € et CA de l'année ≤ 41 250 € | Franchise en base : pas de TVA, pas de déclaration | « TVA non applicable, art. 293 B du CGI » (référence à surveiller, codification en cours [S14]) | [S1] [S2] |
| CA de l'année > 41 250 € | TVA due dès le jour du dépassement : demander un n° de TVA, facturer 20 %, déclarer ; on reste micro-entrepreneur | TVA 20 %, n° TVA intracommunautaire | [S2] [S21] |
| Après la sortie de la franchise | Réel normal, déclaration CA3 (le régime simplifié disparaît au 01/01/2027) ; périodicité à vérifier | — | [S3] |
| Formation exonérée | Déclaration d'activité + attestation 3511-SD | Mention d'exonération (formulation à vérifier) | [S11] |

**Prévision** : la franchise tient pendant l'année de test (~4 500 € de CA). La première année à temps plein (~51 000 €) la dépasserait en cours d'année.

### 2.4 CFE

| Échéance | Obligation | Remarque | Source |
|---|---|---|---|
| 31/12 de l'année de création | Déclaration initiale 1447-C-SD | Y demander les exonérations éventuelles | [S6] [S7] |
| Année de création | Pas de CFE | — | [S6] |
| 15/12 de l'année suivante | 1er paiement | Base réduite de 50 % la 1re année d'imposition ; exonération de la cotisation minimum si CA ≤ 5 000 € (à vérifier) | [S6] [S7] |

### 2.5 Tenue et plafonds

| Quand | Obligation | Remarque | Source |
|---|---|---|---|
| À chaque encaissement | Livre des recettes `suivi/recettes.md` | Obligatoire ; registre des achats en plus | [S19] |
| Chaque trimestre | Vérifier le CA cumulé | Plafond 83 600 €/an en 2026 ; alerte à 80 % (~67 000 €) | [S22] |

## 3. 90 prochains jours (28/10/2026 – 25/01/2027)

| Date | Échéance | Pour OPSESOL | Source |
|---|---|---|---|
| 15/12/2026 | CFE | Non : entreprise non créée | [S6] |
| 31/12/2026 | Déclaration CFE 1447-C-SD | Seulement si le début d'activité est en 2026 (déconseillé) | [S6] [S7] |
| 01/01/2027 | Fin du régime simplifié de TVA | Sans effet tant que vous êtes en franchise | [S3] |
| Dès le début d'activité | Réception des factures électroniques | Choisir une plateforme agréée | [S4] [S5] |

**Conseil : déclarer le début d'activité en janvier 2027.** La CFE ne serait due qu'en décembre 2028 et la déclaration initiale avant le 31/12/2027. La création étant gratuite et rapide, il n'y a rien à gagner à la faire plus tôt tant que le contrat n'est pas vérifié.

| Semaines | À faire (≈ 4 h/semaine) |
|---|---|
| Fin oct. – nov. | Relecture du contrat de travail (priorité 1) ; prendre rendez-vous pour une consultation d'expert-comptable ; devis RC pro |
| Déc. | Choisir l'adresse, la banque et la plateforme de facturation électronique ; préparer la déclaration sur le guichet unique |
| Janv. 2027 | Déclarer le début d'activité ; ouvrir le compte dédié ; souscrire la RC pro ; créer les espaces Urssaf et impots.gouv.fr |

## Points à vérifier

- Taux de formation professionnelle (0,2 %) et taux du versement libératoire (2,2 %), et la condition de revenu fiscal du versement libératoire.
- Votre éligibilité à l'ACRE en étant salarié (conditions 2026).
- L'abattement de 34 % pour les BNC.
- La gratuité de la déclaration sur le guichet unique au moment du dépôt.
- L'obligation de compte bancaire dédié (seuil de 10 000 €).
- Les dates exactes des déclarations Urssaf mensuelles ou trimestrielles.

## Sources (consultées les 21 et 28/10/2026)

| Réf. | Source |
|---|---|
| S1 | impots.gouv.fr, Les régimes d'imposition à la TVA : https://www.impots.gouv.fr/professionnel/les-regimes-dimposition-la-tva |
| S2 | BOFiP, franchise en base : https://bofip.impots.gouv.fr/bofip/849-PGP.html/identifiant=BOI-TVA-DECLA-40-10-10-20260701 |
| S3 | impots.gouv.fr, Le RSI TVA est supprimé à compter du 01/01/2027 : https://www.impots.gouv.fr/actualite/le-regime-simplifie-dimposition-la-tva-est-supprime-compter-du-1er-janvier-2027 |
| S4 | economie.gouv.fr, facturation électronique : https://www.economie.gouv.fr/tout-savoir-sur-la-facturation-electronique-pour-les-entreprises |
| S5 | impots.gouv.fr, guide pratique : https://www.impots.gouv.fr/sites/default/files/media/1_metier/2_professionnel/EV/2_gestion/290_facturation_electronique/guide_pratique_facturation_electronique.pdf |
| S6 | impots.gouv.fr, fiche CET-IFER 2026 : https://www.impots.gouv.fr/sites/default/files/media/3_Documentation/depliants/pro_fiche_cet-ifer_2026.pdf |
| S7 | Notice 1447-C 2026 : https://www.impots.gouv.fr/sites/default/files/formulaires/1447-c-sd/2026/1447-c-sd_5570.pdf |
| S10 | Guichet unique : https://formalites.entreprises.gouv.fr/preparer.php |
| S11 | Formulaire 3511-SD : https://www.impots.gouv.fr/formulaire/3511-sd/demande-dattestation-au-titre-dactivites-sinscrivant-dans-le-cadre-de-la-fpc |
| S12 | Centre Inffo (secondaire) : https://www.centre-inffo.fr/?p=198333 |
| S14 | BOFiP, codification de la TVA dans le CIBS : https://bofip.impots.gouv.fr/bofip/14901-PGP.html/identifiant=BOI-RES-TVA-000253-20261007 |
| S15 | impots.gouv.fr, résultat imposable IR ou IS : https://www.impots.gouv.fr/professionnel/resultat-imposable-limpot-sur-le-revenu-ir-ou-limpot-sur-les-societes |
| S19 | Urssaf, taux des auto-entrepreneurs 2026 : https://www.urssaf.fr/accueil/actualites/taux-cotisations-autoentrepeneur.html ; l'essentiel du statut : https://www.autoentrepreneur.urssaf.fr/portail/accueil/sinformer-sur-le-statut/lessentiel-du-statut.html |
| S20 | Urssaf, ACRE : https://www.urssaf.fr/accueil/exoneration-acre-createur.html ; taux réduits : https://www.urssaf.fr/accueil/outils-documentation/taux-baremes/taux-cotisations-ac-plnr.html |
| S21 | impots.gouv.fr, micro-entrepreneur et TVA : https://www.impots.gouv.fr/professionnel/questions/en-tant-que-micro-entrepreneur-puis-je-etre-redevable-de-la-tva |
| S22 | economie.gouv.fr, dépassement du seuil : https://www.economie.gouv.fr/entreprises/gerer-sa-micro-entreprise/micro-entreprise-que-se-passe-t-il-quand-le-seuil-de-chiffre-daffaires-est-depasse |

À valider avec l'Urssaf ou un expert-comptable.
