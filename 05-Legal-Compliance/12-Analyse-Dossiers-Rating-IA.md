# Tenu — Analyse documentaire et rating des candidats

29 octobre 2026 — Spécification juridique et produit. Module prévu, **non réputé prêt à être activé**.

## 1. Objet, séparations et vocabulaire

Client : propriétaire particulier. Personnes évaluées : candidat locataire et, pour les vérifications nécessaires, garant. La note du candidat est établie à partir de justificatifs autorisés ; ce n'est pas une note du logement.

Séparer trois sorties :
1. complétude et lisibilité des pièces ;
2. cohérence documentaire / signaux à examiner / vérification externe licite ;
3. rating du candidat pour la finalité précisément définie (ex. capacité à faire face au loyer), si et seulement si ses règles et sa licéité ont été validées.

Une pièce manquante ou étrangère n'est pas une fraude. Une anomalie OCR n'est pas une fausse déclaration. La qualité d'image n'est pas une qualité personnelle.

Termes autorisés : « contrôle effectué », « anomalie à examiner », « source vérifiée dans cette limite », « non vérifiable ». Éviter « candidat certifié », « faux document prouvé par IA », « locataire sans risque » et « garantie loyers ».

## 2. Données d'entrée et vérifications

Limiter la collecte aux pièces exigibles selon le bail et la qualité candidat/garant. Prévoir une liste blanche réglementaire versionnée, pas un champ libre demandant « tous documents utiles ». Les pièces superflues sont écartées/retournées/supprimées selon procédure ; ne pas extraire leurs données pour le modèle.

Les équivalents étrangers autorisés, traductions et conversions en euros doivent être acceptés dans les conditions légales. Définir source/date de conversion. Le format non pris en charge conduit à une revue manuelle, pas à une mauvaise note.

Contrôles envisagés, à tester :
- extraction des champs nécessaires, avec confiance OCR ;
- cohérence d'identité entre pièces, périodes, sommes et dates ;
- comparaison de valeurs et détection d'indices de retouche, avec explication localisée ;
- vérification sur source officielle ou service habilité seulement si l'accès, l'usage et les données sont autorisés.

Pas de mots de passe fiscaux, bancaires ou de réseaux sociaux demandés au candidat. Pas de biométrie faciale, d'inférence émotionnelle ou de collecte de données pénales. Les contacts employeur/organisme ne sont pas automatisés sans procédure et fondement préalablement validés.

## 3. Fiche de méthode du rating — à compléter avant calcul réel

| Paramètre | Décision requise |
|---|---|
| Finalité du score | [capacité financière / autre objectif licite précisément défini] |
| Variables admises et raison | [liste, provenance, nécessité et exactitude] |
| Variables exclues / proxies | Origine, nationalité, nom, langue, âge, santé, famille et autres critères protégés ; contrôles de proxies |
| Formule, pondérations et échelle | [règles publiables, version, justification ; aucune valeur inventée dans ce projet] |
| Données insuffisantes | « Non évalué / revue nécessaire », pas de score zéro automatique |
| Date et validité | [date de calcul, actualité des pièces, expiration et recalcul] |
| Seuils | [usage informatif et limites ; aucun seuil de rejet automatique] |
| Modèle et périmètre | [versions, langues/pays documentaires supportés et exclusions] |
| Explication individuelle | [facteurs effectivement utilisés et incertitudes] |
| Réexamen | [canal, délai, responsable et possibilité réelle de modifier la sortie] |
| Partage et durée | Dossier courant et destinataires habilités ; pas de fichier transversal de réputation |

L'invitation ou l'acceptation des CGV par le bailleur ne vaut pas consentement explicite du candidat à un profilage. Si une base légale, une information ou une exception particulière est nécessaire, elle est documentée séparément, sans la présumer libre dans un contexte de candidature.

## 4. Décision et contestation

Le propriétaire examine les éléments, peut demander une pièce autorisée/correction et décide réellement de l'attribution. Il doit pouvoir écarter la note et sa décision ne doit pas être un clic d'approbation systématique. Interdire le rejet automatique et le classement éliminatoire invisible par défaut ; une recommandation déterminante peut conserver les effets d'une décision automatisée.

Informer le candidat avant traitement : finalités, données, rôle de l'IA, destinataires, portée et conséquences, logique utile du score, durée, droits et voie de correction/contestation. Communiquer une explication compréhensible sans se limiter à « l'algorithme a décidé ». Prévoir accès/correction aux éléments qui le concernent sans exposer les autres candidats ou secrets disproportionnés.

Le statut « anomalie à vérifier » ne doit pas devenir une accusation communiquée à d'autres bailleurs. Le candidat peut présenter des explications ; la revue est enregistrée et les erreurs corrigées à la source et dans les dérivés. Les traductions de la notice et des explications sont versionnées.

## 5. Qualification RGPD et AI Act

Établir une analyse distincte par module : OCR/complétude, recherche de fraude documentaire et score de solvabilité ne se confondent pas.

La note personnelle peut constituer un profilage ; examiner l'article 22 et réaliser une analyse d'impact adaptée avant mise en œuvre compte tenu du traitement et de ses effets. La nécessité d'une consultation préalable de l'autorité dépend des risques résiduels et des textes.

Si le score évalue la solvabilité ou crée un score de crédit, examiner l'annexe III, point 5(b), de l'AI Act. La Commission donne des exemples de scores réutilisés pour l'accès au logement. Une fonction limitée à la détection de fraude financière peut avoir un régime différent, mais appeler l'ensemble « anti-fraude » ne suffit pas à sortir le rating de cette analyse.

Documenter fournisseur/déployeur, destination, catégorie, textes et calendrier effectif au lancement. Si régime haut risque applicable : constituer le dispositif requis (risques, données, documentation, journaux, contrôle humain, qualité, exactitude, robustesse, conformité et suivi) selon obligations et échéances applicables. Ne pas annoncer une conformité acquise, un enregistrement ou une évaluation inexistants.

## 6. Recette et preuves

- Corpus légalement constitué, sans réutiliser les dossiers clients pour entraînement ; tests distincts.
- Mesures de faux positifs/négatifs et d'abstention par types de pièces, langues, pays de documents et qualité de scan.
- Tests de biais/proxies, accès et fuites, prompt injection dans un document et fichier malveillant.
- Validation humaine des règles et des cas limites ; tests d'un candidat expatrié avec revenus étrangers et d'un dossier incomplet.
- Réexamen réel, corrections propagées, expiration, journal de version et retour d'incident.
- Validation juridique, protection des données, produit et technique, avec preuves datées avant activation.

Ne pas évaluer les candidats par reconnaissance de l'origine ou de traits sensibles pour « mesurer le biais » sans fondement et protocole autorisés.

## 7. Conservation distincte

Les justificatifs, extractions et ratings ne suivent pas la purge des médias à douze mois après sortie. Pour candidat non retenu : proposition de travail de suppression des pièces opérationnelles sous 30 jours après clôture/notification, à valider ; archive de preuve éventuelle séparée et minimisée, avec motif/durée propres. Cette proposition n'est ni une durée légale ni une autorisation de garder tous les dossiers.

Pour candidat retenu : conserver seulement ce qui reste nécessaire à la location et aux obligations, revoir les copies d'identité et pièces financières ; pas de maintien automatique du score ou des revenus initiaux pendant tout le bail. Chaque sortie a son calendrier et les journaux ne reproduisent pas tous les justificatifs.

Sources : [CNIL justificatifs](https://www.cnil.fr/fr/location-dun-bien-immobilier-quels-justificatifs), [CNIL profilage](https://www.cnil.fr/fr/profilage-et-decision-entierement-automatisee), [Commission essential services](https://ai-act-service-desk.ec.europa.eu/en/essential-services), [annexe III](https://ai-act-service-desk.ec.europa.eu/en/ai-act/annex-3).
