# Tenu — Registre des risques B2B France

Version 2.0 — 28 octobre 2026  
Revue mensuelle ; prochaine revue proposée : 28 novembre 2026.  
Périmètre : agences immobilières en France, états des lieux signés assistés par IA, pilote 30 jours puis engagement 12 mois facturé mensuellement et poursuite mensuelle avec préavis de 30 jours.

Les évaluations ci-dessous sont initiales et qualitatives ; risques résiduels à réévaluer après preuve des contrôles. Les responsables sont des rôles proposés, à attribuer nominativement. Aucune action n'est considérée achevée.

## Critères

Critique : menace sur la validité/intégrité des dossiers ou exposition majeure ; traitement avant dossiers réels. Élevé : risque substantiel contractuel, opérationnel ou commercial ; traitement avant paiement ou étape précisée. Moyen : suivi avec plan daté. Probabilité estimée et impact doivent être confirmés sur l'architecture effective.

## Risques et traitement

| ID | Risque / conséquence | Probabilité | Impact / priorité | Contrôles attendus | Responsable proposé | Échéance |
|---|---|---|---|---|---|---|
| C1 | État des lieux incomplet, non contradictoire ou mal signé ; preuve contestée | Moyenne | Majeur / critique | Mentions légales, mandats, lecture complète, réserves, identification, signature et preuve d'intégrité | Juridique + produit | Avant dossiers réels |
| C2 | Dossier d'une agence accessible à une autre ; fuite de photos/données | Moyenne | Majeur / critique | Tests d'isolation, rôles, stockage privé, contrôle liens et exports, incidents | Technique + données | Avant dossiers réels |
| C3 | Perte/altération des originaux, annexes ou preuves ; remise absente | Moyenne | Majeur / critique | Version signée figée, preuve de remise à chacun, sauvegardes/restauration et export testés | Technique | Avant dossiers réels |
| H1 | IA invente un défaut ou confond vétusté et dommage ; retenue injustifiée | Élevée | Élevé | Vérification humaine obligatoire, distinction suggestion/constat, corrections tracées ; pas de décision automatique de retenue | Produit + juridique | Avant dossiers réels |
| H2 | Traduction trompeuse pour un expatrié ; consentement contesté | Moyenne | Élevé | Statut des traductions, relecture, réserves et compréhension avant signature | Produit | Avant dossiers réels |
| H3 | Qualification RGPD erronée, prestataires/transferts non maîtrisés | Moyenne | Élevé | Cartographie effective, article 28, bases et information, contrôle des API IA et transferts | Données + juridique | Avant dossiers réels |
| H4 | Suppression trop précoce ou conservation excessive | Moyenne | Élevé | Calendrier par catégorie, analyse probatoire, gel contentieux ciblé et purge vérifiée | Juridique + technique | Avant dossiers réels |
| H5 | Panne sur place ou signature/remise en échec | Moyenne | Élevé | Procédure de secours, absence de signature simulée, reprise contrôlée, alertes et assistance | Technique + opérations | Avant dossiers réels |
| H6 | Clauses annuelles, quotas ou dépassements mal compris ; contestation commerciale | Moyenne | Élevé | Bon de commande explicite, prix initial fixe, acceptation payante, préavis et simulations de résiliation | Commercial + juridique | Avant paiement |
| H7 | RC Pro inadaptée ou responsabilité contractuelle non assurée | Moyenne | Élevé | Confirmation écrite de couverture et régime de responsabilité validé | Direction + juridique | Avant dossiers réels |
| H8 | Réutilisation des dossiers par fournisseur IA ou finalité non autorisée | Moyenne | Élevé | Conditions fournisseur, configuration, minimisation et interdiction d'entraînement dans le périmètre sous-traité | Données + technique | Avant dossiers réels |
| M1 | Faible adoption agence ou coût IA/signature supérieur à la marge | Moyenne | Moyen | Pilote limité, métriques de conversion, usage, coût par dossier et renouvellement | Commercial + finance | Avant fixation des prix puis mensuel |
| M2 | Engagement commercial au-delà des capacités réelles | Moyenne | Élevé | Validation technique des SLA, archivage et exports ; pas de conformité/certification non démontrée | Direction + technique | Avant paiement |
| M3 | Confusion agence cliente / accord du locataire | Moyenne | Élevé | Séparer paiement et consentement, préserver observations contradictoires et accès aux exemplaires | Produit + juridique | Avant dossiers réels |
| M4 | Évolution réglementaire ou destination IA mal qualifiée | Moyenne | Élevé | Analyse AI Act documentée, veille, exclusion des usages non validés | Juridique + produit | Avant dossiers réels puis trimestriel |
| M5 | Dépendance fournisseur ou personne clé | Moyenne | Moyen | Documentation, suppléance, export et réversibilité testés | Direction + technique | Avant paiement puis trimestriel |
| M6 | Ancienne documentation B2C/UK ou prix à l'acte encore présentés | Élevée | Moyen | Inventaire et réalignement docs, site, application, contrats et facturation | Produit + commercial | Avant commercialisation |

## Suivi des actions

Pour chaque risque, consigner dans le suivi d'équipe : responsable nominatif, échéance datée, contrôle testé, preuve, résultat, risque résiduel et décision d'acceptation. Le responsable juridique pilote les risques juridiques ; la direction accepte le risque résiduel commercial et opérationnel avec les responsables concernés.

Les risques critiques ne sont pas clos par la seule rédaction d'une clause ou d'un avertissement IA.

## Références

- [Cadre juridique et commercial](../05-Legal-Compliance/02-Cadre-B2B-Agences-France.md)
- [Checklist de lancement](../05-Legal-Compliance/01-Legal-Checklist.md)
- [Conditions d'abonnement proposées](../05-Legal-Compliance/03-Projet-Conditions-Abonnement-B2B.md)
- [Annexe RGPD et sécurité](../05-Legal-Compliance/04-Projet-Annexe-RGPD-Securite.md)

Ce registre remplace l'évaluation du 2 avril 2026 centrée sur la vente directe aux locataires en France/Royaume-Uni. Les anciens décomptes de risques et dates de lancement ne sont plus utilisés.
