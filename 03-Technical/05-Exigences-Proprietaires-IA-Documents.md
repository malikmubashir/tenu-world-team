# Tenu — Exigences techniques de la nouvelle offre propriétaires

29 octobre 2026 — Spécification à implémenter/recetter ; aucune modification du code ni configuration fournisseur n'est prouvée par ce fichier.

## Modèle et autorisations

Entités : propriétaire, logement, candidature, candidat/garant, document/version, contrôle, note/version/explication, bail/version/langue, EDL/éléments, média/phase/repères, réserve, signature/preuve, événement de conservation/gel/export.

Lier les droits au rôle et au dossier ; tests d'accès croisés obligatoires. Liens d'invitation limités et révocables. Un compte support ne donne pas accès courant à toutes les pièces. Pas de table transversale de réputation des candidats.

## Traitements séparés et sorties structurées

OCR, contrôle documentaire, score, bail, traduction et analyse de médias sont des traitements identifiés avec entrée, sortie, règles et version. Un changement de modèle ne réécrit pas un signé ou une décision passée.

Le document candidat est une donnée non fiable, jamais une instruction système : neutraliser prompt injections, liens actifs et fichiers malveillants. Extraire seulement les champs autorisés ; origine/nationalité/langue ne deviennent pas facteurs de risque.

Contrôle : référence de pièce, champ/indice, source de vérification réelle, date, résultat et limite. Sans contrôle fiable : non vérifiable. Ne pas générer d'appel externe fictif ni de statut authentifié.

Rating : formules/règles validées indépendamment du LLM ; valeurs, provenance, facteurs, version, abstention et expiration conservés. Module non activé tant que la fiche méthode et les préalables légaux ne sont pas validés. Pas de refus automatique.

Bail : moteur de règles/clauses validées et modèle réglementaire versionné. Valeur manquante => champ bloquant/revue ; aucune hallucination de DPE, loyer local, pouvoir, taux, date ou annexe.

Médias : guidage et contrôle des prises, vidéo/transcodage, images extraites avec timecode, comparaison et abstention. Pas d'image générée pour combler un constat.

## Sécurité, fournisseurs et conservation

Classification plus forte pour identités/revenus. Chiffrement/transferts et fournisseurs vérifiés par module ; ne pas envoyer un dossier complet à un modèle sans nécessité. Interdiction d'entraînement contractuelle et paramétrée pour chaque offre ; pas de promesse ZDR sans preuve.

Jobs distincts : médias séparés douze mois après sortie effective ; caches/OCR plus courts ; candidatures/scores selon leurs calendriers ; PDF signés et preuve selon calendrier documentaire. Propagation des corrections/effacements aux dérivés. Sauvegardes rejouent les suppressions.

Média original, miniature/transcode, audio/transcription, extraction, note et PDF sont référencés dans un inventaire. La purge vidéo doit révoquer les accès, sans casser silencieusement la promesse de livraison d'un dossier signé.

## Signature et langues

Préserver référence française et toutes traductions relues ; liaison de versions. Remise des annexes réellement consultées. Le fournisseur eIDAS, niveau exact, vérification et dossier de preuve sont à confirmer. Contrôle du pouvoir, pas de signature automatique à la place du locataire.

## Test/activation

Tests métier/juridiques et tests sécurité avec corpus légal. Définir faux positifs/négatifs et abstention par types/langues de pièces. Journaux minimisés. Feature flags séparés pour analyse documentaire/rating/bail/vidéo ; activation selon preuves de validation et non seule présence d'un prompt.

Référence : produit et Legal 04, 11 à 14. Les anciennes architectures/prompts no-code restent historiques.
