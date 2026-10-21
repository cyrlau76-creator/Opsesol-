---
description: Émettre une facture (ex. /facture D-2026-003 ou /facture Client X, 1 200 € HT)
argument-hint: numéro de devis ou client + prestation + montant
---
Utilise l'agent `facturation` pour émettre une facture à partir de : $ARGUMENTS
Vérifie toutes les mentions obligatoires, la numérotation continue, enregistre la facture,
mets à jour `suivi/factures.md` et fournis un brouillon d'e-mail d'envoi.
