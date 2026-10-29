# TENU — Business Assumptions : économie, opérations, décisions
**29 octobre 2026 | Registre d'hypothèses V1, non approuvé par les directions**

## 1. Hypothèses structurantes et degré de validation

| ID | Hypothèse | État | Preuve/validation attendue | Responsable proposé |
|---|---|---|---|---|
| H01 | Propriétaires particuliers payeurs ; candidats non payeurs | Aligné avec Finance, Marketing, Produit et Juridique | Parcours et contrat validés | Direction |
| H02 | L'analyse des dossiers réduit le temps de sélection | Non testé | Pilote, temps moyen et erreurs | Produit/Opérations |
| H03 | Le rating est licite, explicable et non discriminatoire | **Bloquant, non validé** | Qualification AI Act/RGPD, AIPD, tests, gouvernance, revue humaine | Juridique/Produit |
| H04 | L'EDL photo/vidéo évite certains déplacements | Non testé | Procédure contradictoire validée, taux de dossiers sans visite | Juridique/Opérations |
| H05 | Les preuves réduisent les litiges et pertes de dépôt | Non démontré | Cohortes comparables, suivi litiges, réserves et décisions | Opérations |
| H06 | Coût TENU inférieur à l'agence à prestation équivalente | Non démontré | Benchmark prix et périmètres, temps propriétaire inclus | Finance/Marketing |
| H07 | Prix dégressif par élément améliore conversion et marge | Non testé | Tests de prix, courbe de coûts et contribution | Finance |
| H08 | Propriétaires disposés à accueillir dossiers internationaux | Non quantifié | Enquête et pilotes, mesure sans critère discriminatoire | Marketing |
| H09 | Fonctionnement multilingue suffisamment exact | Non testé | Relectures, erreurs de traduction, compréhension | Produit/Juridique |
| H10 | Stockage vidéo et conservation sont soutenables | Non chiffré | Poids médian, coûts, durée bail + 12 mois post-sortie | Finance/Technique |

## 2. Grille dégressive — décisions à prendre
Proposition de mécanisme **par tranches marginales**, sans chiffres inventés :

| Palier | Quantité d'éléments vérifiés | Prix marginal TTC/élément | Statut |
|---|---|---|---|
| A | 1 à `q1` | `p1` | À fixer |
| B | `q1+1` à `q2` | `p2 < p1` | À fixer |
| C | `q2+1` à `q3` | `p3 < p2` | À fixer |
| D | Au-delà de `q3` | `p4 < p3` | À fixer |

Éléments = unités définies de checklist d'entrée (pièce, équipement ou constat ? **à trancher**). Les éléments non vérifiés ne doivent pas être artificiellement comptés comme vérifiés. Afficher estimation, compteur, validation, plafond éventuel, frais additionnels et prix total avant commande. Préciser si l'état des lieux de sortie est inclus, facturé à part ou en pack. Contrôle de marge par palier, pas seulement panier moyen.

## 3. Unité économique et coûts
- **Recettes par cycle** = EDL entrée + modules dossier/bail/sortie optionnels achetés, nets des remboursements ; aucune valeur chiffrée validée.
- **Coûts variables** = paiement + OCR/pièces/candidats + revue humaine + génération documents + signature + photo/vidéo + stockage pendant bail + conservation post-sortie + support + incidents.
- **Marge contributive** = recettes HT − coûts variables HT ; simuler N=20, 50, 100, 200 éléments **uniquement comme scénarios**.
- **Point mort** = charges fixes / marge contributive moyenne par transaction, si marge positive.
- **CAC propriétaire** = dépenses d'acquisition / nouveaux propriétaires payeurs ; **LTV** = contribution par cycle × nombre attendu de cycles achetés, avec fréquence observée.
- **Scénarios** prudent/central/haut : conversion, panier, mix modules, erreurs OCR, réexamens, réclamations, vidéo et rotation ; pas de projection de CA validée.

## 4. Chaîne opérationnelle proposée
| Étape | Contrôle qualité / SLA à définir | Risque |
|---|---|---|
| Inscription bailleur et logement | Droits/pouvoirs, régime du bail, éligibilité | Mauvaise qualification |
| Invitation candidats | Notice, pièces autorisées, cloisonnement | Collecte excessive, fuite |
| Analyse pièces | OCR, anomalies explicables, revue humaine | Faux positif, discrimination |
| Rating éventuel | Module désactivé avant feu vert conformité | Profilage illégal |
| Bail/signature | Modèles versionnés, relecture, remise | Clause ou signature invalide |
| Checklist entrée | Éléments réellement vérifiés, photos/vidéos, réserves | Captures incomplètes |
| Contradictoire | Accord, réserves et refus tracés | Preuve unilatérale |
| Vie du bail | Accès restreint, demandes, stockage, support | Coûts longs et fuite |
| Sortie | Comparaison, vétusté/dégradation possible, abstention | Retenue abusive |
| Purge/export | Calendriers par catégorie, gel ciblé | Suppression prématurée ou excessive |

## 5. Arbitrages transverses à obtenir
1. **Finance** : définition élément facturable, seuils, prix TTC, packs, coût complet vidéo, contribution et politique de remboursement.
2. **Marketing** : proposition de valeur prouvable, canal propriétaire, test d'appétence et comparaison rigoureuse aux agences.
3. **Produit/Technique** : checklist configurable, horodatage/provenance, export, rôle de chaque partie, abstention IA, coût média.
4. **Juridique** : justificatifs autorisés, qualification du rating, discrimination, AIPD/AI Act, contradictoire, signature, durée de conservation, qualification de l'activité.
5. **Opérations** : revue humaine, support, résolution des litiges, processus de purge, contrôle qualité et seuils de service.
6. **Direction** : périmètre MVP : proposer **phase 1 sans rating**, avec contrôle documentaire et EDL guidé ; activer rating uniquement après validation formelle.

## 6. Sources internes actives
- `04-Financial/03-Modele-Financier-V2-Guide.md`, `04-Financial/04-Hypotheses-Proprietaires.md`.
- `06-Marketing-GTM/01-GTM-Plan.md`, `06-Marketing-GTM/01-fiche-presentation.md`.
- `02-Product/01-Product-Specification.md`.
- `05-Legal-Compliance/11-Cadre-Proprietaires-Parcours-Location.md`, `12-Analyse-Dossiers-Rating-IA.md`.
- **Pas de dossier Operations dédié repéré dans l'arborescence GitHub consultée** ; ce plan est une proposition à valider, et non la synthèse d'un document opérationnel identifié.

**Ce registre n'altère ni les hypothèses financières historiques ni les documents des autres directions.**
