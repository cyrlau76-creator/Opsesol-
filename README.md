# Opsesol — bureau virtuel de ma SASU

Une équipe d'agents Claude Code pour gérer une SASU avec très peu de temps.
Les agents **préparent** (documents, calculs, brouillons), vous **validez**.

## Démarrage (15 minutes, une seule fois)

1. Compléter `entreprise/profil.md` : identité, offre, régimes, conditions de paiement.
2. Ouvrir Claude Code dans ce dossier et lancer `/echeances` pour générer votre calendrier
   d'obligations (et la checklist de création si la société n'est pas encore immatriculée).
3. Lancer `/point-hebdo` : vous obtenez vos 3 priorités de la semaine.

## Routine conseillée (≈ 30 min / semaine)

| Quand | Commande | Ce que vous obtenez |
|---|---|---|
| Lundi, 10 min | `/point-hebdo` | Priorités, échéances, relances dues |
| Quand un client dit oui | `/devis …` puis `/facture …` | Documents conformes et numérotés |
| Vendredi, 5 min | `/relance` | Relances des impayés prêtes à envoyer |
| Une fois par semaine | `/post …` | Un post LinkedIn en 2 variantes |
| Chaque trimestre | `/echeances` | Calendrier fiscal et légal à jour |

Vous pouvez aussi parler librement : « prépare la décision d'approbation des comptes »,
« compare salaire et dividendes pour 30 000 € de bénéfice », « écris un e-mail de
prospection pour les PME du BTP »… L'agent adapté est choisi automatiquement.

## L'équipe

| Agent | Rôle |
|---|---|
| `assistant-direction` | Trie, priorise, délègue, fait le point hebdo |
| `juriste-sasu` | Création, statuts, décisions de l'associé unique, contrats, CGV, RGPD |
| `comptable-fiscal` | TVA, IS, rémunération / dividendes, frais, trésorerie, calendrier |
| `facturation` | Devis, factures, avoirs, numérotation, relances |
| `commercial` | Offre, prospection, propositions, pipeline |
| `marketing-contenu` | LinkedIn, site web, newsletter |

## Organisation des fichiers

```
CLAUDE.md            Règles communes à tous les agents
entreprise/profil.md Informations de la société (à compléter)
.claude/agents/      Définition des agents
.claude/commands/    Commandes rapides (/point-hebdo, /devis, …)
modeles/             Modèles de devis et de facture
suivi/               Registres : factures, devis, pipeline, échéances, tâches, contenus
documents/           Documents générés, classés par année et par type
```

## Limites

- Les agents ne remplacent pas un expert-comptable ni un avocat : ils préparent le travail
  et signalent ce qui doit être validé.
- Les taux et seuils fiscaux changent chaque année : les agents les vérifient sur les sites
  officiels, mais relisez toujours les chiffres.
- Aucun envoi, paiement ni dépôt n'est fait sans votre accord.
- Ne stockez pas de données sensibles (RIB complet, mots de passe) dans ce dépôt.

## Application de pilotage

`app/pilotage.html` est publiée comme page privée sur claude.ai : https://claude.ai/artifact/4LfWNXSgCNQ7vpzUeDxVPw

- **Accueil** : prérequis bloquant, tâches, pipeline, 90 prochains jours.
- **Prospects** : test de conflit en 5 questions, étape, prochaine action, notes.
- **Diagnostic** : les 25 questions du diagnostic opérationnel, scores par domaine, restitution rédigée par l'agent commercial.
- **Agents** : les 6 agents, qui voient le profil, les tâches et les prospects, et peuvent ajouter une tâche.

Les données de l'appli (prospects, tâches, diagnostics) sont stockées dans la page sur claude.ai, pas dans ce dépôt.
Les agents de l'appli reprennent les rôles de `.claude/agents/`, mais ne modifient pas les fichiers du dépôt.
