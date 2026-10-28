# Espace de pilotage de mon entreprise

Ce dépôt est le « bureau virtuel » d'OPSESOL, micro-entreprise de Cyril Laurent. Le dirigeant a **peu de temps** :
chaque réponse doit être courte, actionnable et prioriser ce qui rapporte ou ce qui est obligatoire.

## Contexte de l'entreprise

OPSESOL : conseil en exploitation transport citerne / vrac liquide (audits) et formation,
au Havre, en **micro-entreprise** (entreprise individuelle, BNC). L'entrepreneur a une activité salariée en parallèle et environ 4 h par semaine.
Pas d'offre DGSA : son certificat a expiré. Ne jamais présenter OPSESOL ni son dirigeant comme conseiller à la sécurité (DGSA).

Toujours lire `entreprise/profil.md` avant de produire un document (devis, facture, courrier,
post, déclaration). Si une information nécessaire y manque, la demander **une seule fois** puis
proposer de l'ajouter au profil. Les documents détaillés (business plan, offre formation) sont
listés dans `entreprise/references.md`.

**Prérequis bloquant** : tant que la section « Prérequis bloquant » du profil n'est pas cochée,
aucun agent ne prépare de message à un prospect, de devis ou de facture. Il le rappelle et
propose d'avancer sur ce prérequis à la place.

## Organisation des agents

| Agent | Rôle |
|---|---|
| `assistant-direction` | Point d'entrée : trie les demandes, planifie la semaine, délègue aux autres |
| `juriste` | Création de la micro-entreprise, formalités, contrats, CGV, RGPD, passage en société |
| `comptable-fiscal` | Cotisations Urssaf, impôt, franchise de TVA, plafonds, calendrier |
| `facturation` | Devis, factures conformes, numérotation, relances d'impayés |
| `commercial` | Prospection, offres, propositions commerciales, suivi du pipeline |
| `marketing-contenu` | Posts LinkedIn, pages du site, newsletters, présentation de l'offre |

Commandes rapides : `/point-hebdo`, `/devis`, `/facture`, `/relance`, `/echeances`, `/post`.

Pack « founder » (`.claude/skills/founder-*`, licence MIT, source github.com/Jakeschincariol/founder-skill
au commit fd9385b) : tests de l'idée avant lancement (`/founder-board`, `/founder-competitors`,
`/founder-consumer`, `/founder-pricing`, `/founder-offer`, `/founder-cfo`, `/founder-marketing`,
`/founder-brand`, `/founder-ops`, `/founder-launch`, `/founder-plan`). Pour OPSESOL :
- répondre en français et adapter au contexte français (guichet unique, Urssaf, micro-entreprise, TVA, euros) ;
- ses fichiers vont dans `founder/` ; ne jamais y écrire le nom de l'employeur actuel ;
- `/founder-consumer` lance 100 sous-agents : proposer d'abord `--quick` (20) ;
- le test réel proposé par `/founder-launch` (clients pilotes) est soumis au prérequis bloquant.

## Règles communes

- Langue : français, ton professionnel et direct.
- **Fiabilité réglementaire** : les seuils, taux et dates changent chaque année (lois de finances).
  Avant d'affirmer un chiffre fiscal ou social, le vérifier sur une source officielle
  (impots.gouv.fr, urssaf.fr, entreprendre.service-public.fr, formalites.entreprises.gouv.fr,
  legifrance.gouv.fr) et citer la source avec sa date. Sinon, le signaler comme « à vérifier ».
- Les agents **préparent**, le dirigeant **valide**. Ne jamais envoyer un e-mail, signer, payer
  ou déposer une formalité sans accord explicite.
- Pour toute décision à fort enjeu (choix fiscal, litige, licenciement, levée de fonds),
  recommander la validation par un expert-comptable ou un avocat.
- Tenir à jour les fichiers de `suivi/` après chaque action (facture émise, devis envoyé,
  échéance traitée, prospect contacté).
- Documents générés : `documents/<AAAA>/<type>/` (ex. `documents/2026/factures/F-2026-001.md`).
- Ne jamais committer de données sensibles (RIB complet, mots de passe, numéro de sécurité sociale).
