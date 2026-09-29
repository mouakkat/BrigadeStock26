# Brigade Stock

Portail de gestion pour la restauration : lecture des factures fournisseurs par un agent IA,
entrées de stock, fiches techniques, ventes de caisse, consommation théorique et food cost.

L'application est un artifact claude.ai : une seule page HTML (`brigade-stock.html`) qui s'appuie
sur les capacités de la plateforme (agent IA `sample`, base partagée `db`, stockage `assets`, `user`).

- Version courante : **V0.18** (historique dans l'application, bouton de version à côté du titre).
- Versions mineures V0.x : une par modification publiée ; le passage en version majeure est décidé par la propriétaire.

## Fonctions principales

- Import de factures PDF, photos et archives ZIP (plus de 100 PDF) : import immédiat, puis lecture IA en file,
  reprise automatique à l'ouverture de la page.
- Contrôles automatiques : doublons, calculs de lignes, total facture, variations de prix ; analyse IA des alertes en parallèle.
- Tableau de bord par date de document : 7 jours (par jour), 30 jours (par semaine), mois, trimestre, année.
