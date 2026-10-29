# TENU — Business Model Canvas V3 (9 blocs)
**29 octobre 2026 | Proposition stratégique à valider | Marché initial : France, résidence principale vide/meublée | Payeur : propriétaire particulier**

> **Positionnement :** TENU accompagne les propriétaires particuliers louant notamment à des étudiants internationaux et professionnels expatriés, de la candidature à la sortie, avec vérifications documentaires explicables et état des lieux photographique/vidéo contradictoire. Le candidat n'est pas facturé.

| Bloc | Hypothèses et choix |
|---|---|
| **1. Segments de clientèle** | **Client payeur :** propriétaires particuliers de logements vides/meublés en France, en particulier ceux exposés aux candidatures internationales, aux locations à distance et à la rotation locative. **Utilisateurs non payeurs :** candidats, locataires, garants, mandataires autorisés. Pas d'offre agence payante dans le périmètre actuel. |
| **2. Proposition de valeur** | **Propriétaire :** moins de déplacements si état des lieux à distance légalement réalisable ; alternative potentiellement moins coûteuse qu'une prestation d'agence à périmètre comparable ; collecte et contrôle de cohérence des justificatifs ; aide humaine à la décision appuyée par des signaux explicables ; messagerie et traduction ; preuves photo/vidéo datées, réserves, comparaison entrée/sortie ; meilleure traçabilité juridique (sans garantie de résultat). **Locataire :** transparence, possibilité de réserves, documents multilingues, accès aux preuves, réduction *possible* des contestations de dépôt et sérénité. |
| **3. Canaux** | Site/application Tenu.world, contenu SEO « louer à un expatrié », communautés de bailleurs, associations de propriétaires, réseaux de relocation comme prescripteurs, partenariats avec universités et employeurs pour la sensibilisation ; acquisition directe B2C. |
| **4. Relations clients** | Onboarding propriétaire, parcours self-service, assistance sur anomalies et traductions, notifications, support multilingue proportionné, droit de correction/réexamen des candidats, espace partagé avec droits séparés, service après-vente et export. |
| **5. Sources de revenus** | **Vente à l'acte au propriétaire**. Prix principal de l'état des lieux selon nombre d'éléments effectivement vérifiés, avec **prix unitaire dégressif par tranches** et règles explicites de facturation. Modules de contrôle de dossier, bail, signature, analyse de sortie à facturer séparément ou en packs si validés. Aucun prix TTC ni mix commercial validé ; pas de frais imposés au candidat ni abonnement agence. |
| **6. Ressources clés** | Application et checklist configurable, moteurs OCR et IA, équipe produit/technique, expertise juridique et immobilière FR, modèles de baux validés, stockage sécurisé et export des preuves, mécanismes de signature, gestion des rôles, suivi de conformité RGPD/AI Act, support client. |
| **7. Activités clés** | Acquisition de bailleurs ; qualification des logements ; collecte minimale de pièces autorisées ; contrôles documentaires et revue humaine ; développement/validation éventuelle du rating ; états des lieux guidés, contradictoires, photos/vidéos et réserves ; comparaison entrée/sortie ; gestion des preuves et purge ; qualité, sécurité, SAV et mesure des résultats. |
| **8. Partenaires clés** | Experts juridiques, prestataires d'identité/vérification *autorisée*, signature électronique, hébergement/stockage, fournisseurs IA, assureur, associations de propriétaires, relais universitaires/relocation (prescripteurs, non clients contractuels dans l'offre actuelle). |
| **9. Structure des coûts** | Coûts fixes : développement, sécurité, conformité, juridique, assurance, maintenance, marketing et support. Variables : OCR/contrôles par candidature, éventuelle revue humaine, IA, photos/vidéos (stockage/transcodage/bande passante), signatures, traduction, support, paiements, remboursements, réexamens et conservation probatoire. Calcul par dossier et par cycle locatif. |

## Architecture de l'offre et parcours
1. **Candidature :** invitation, collecte des seules pièces autorisées, contrôles de lisibilité/cohérence, sources vérifiées seulement si habilitées. Résultats « cohérent sur les contrôles réalisés », « anomalie à examiner », « non vérifiable ».
2. **Rating candidat :** **module conditionnel, non activable sans validation** de la finalité, variables, pondérations, tests de biais, AIPD/AI Act, explication, contestation et revue humaine réelle. Aucune décision automatique de refus ; ni nationalité, ni origine, ni langue comme facteur défavorable.
3. **Bail :** modèle réglementaire versionné, relecture et signature réelle des parties ; uniquement après validation juridique du périmètre.
4. **Entrée :** checklist pièce/élément, médias proportionnés, réserves, compteurs/clés, accord contradictoire et export. État des lieux à distance seulement lorsque la procédure le permet ; une capture unilatérale n'est pas suffisante.
5. **Sortie :** comparaison guidée, aide à distinguer vétusté/dommage possible/indéterminé ; décision humaine, justificatifs distincts pour toute retenue ; archivage et purge par type de donnée.

## Hypothèse de tarification dégressive — formule sans prix inventé
Définir `N` = nombre d'éléments **validés comme contrôlés** à l'entrée ; `q1,q2,q3` = seuils contractuels et `p1>p2>p3>p4` = tarifs unitaires TTC par tranche, tous à fixer.
**Prix EDL(N) = p1×min(N,q1) + p2×min(max(N−q1,0),q2−q1) + p3×min(max(N−q2,0),q3−q2) + p4×max(N−q3,0).**
Éventuel minimum de commande, plafond, quotas photo/vidéo, prix sortie et frais de stockage doivent être **annoncés avant achat**. Vérifier la résistance à la sous-déclaration d'éléments et les effets de seuil. Ne pas facturer au candidat.

## Risques majeurs et garde-fous
- **Discrimination et profilage :** notation de personnes potentiellement réglementée, biais contre documents étrangers, RGPD art. 22 et AI Act ; scoring à suspendre jusqu'aux validations requises.
- **Preuve juridique :** état des lieux contradictoire, signatures, réserves, conservation et export ; pas de « sécurité juridique garantie ».
- **Économie :** la dégressivité peut détruire la marge sur gros inventaires ; chiffrer vidéo, support, stockage sur durée du bail, revue humaine et conformité.
- **Promesses :** économies par rapport aux agences et baisse des litiges **à démontrer par comparaison de services équivalents et pilotes**.
- **Géographie :** France d'abord ; Royaume-Uni et autres types de baux exclus du MVP actuel.

## Cohérence avec les directions (documents consultés le 29/10/2026)
- **Finance :** `04-Financial/03-Modele-Financier-V2-Guide.md` et `04-Hypotheses-Proprietaires.md` : prix non validés, ancien modèle historique, calcul marge par lot/cycle.
- **Marketing :** `06-Marketing-GTM/01-GTM-Plan.md` et `01-fiche-presentation.md` : propriétaire payeur, acquisition directe, promesses prudentes.
- **Produit :** `02-Product/01-Product-Specification.md` : fonctionnalités projetées et non prouvées implémentées.
- **Juridique :** `05-Legal-Compliance/11-Cadre-Proprietaires-Parcours-Location.md` et `12-Analyse-Dossiers-Rating-IA.md` : périmètre, rating, contradictoire.
- **Opérations :** aucun dossier de direction « Operations » autonome identifié dans l'arborescence du dépôt à la date de revue. Hypothèses opérationnelles proposées dans le document dédié ; elles ne constituent pas une validation de cette direction.
