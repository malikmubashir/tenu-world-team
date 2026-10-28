# Tenu — Projet d'annexe RGPD et sécurité

28 octobre 2026 — Trame à compléter et contractualiser avant tout pilote contenant des données réelles.  
Ce document ne certifie pas l'état technique du service.

## 1. Qualification et description

Hypothèse : l'agence détermine les finalités des dossiers et Tenu agit sur ses instructions comme sous-traitant. Vérifier si l'agence agit elle-même comme sous-traitant d'un bailleur ou si une autre qualification s'impose. Les finalités commerciales propres de Tenu sont décrites dans une information distincte et ne sont pas assimilées aux instructions de l'agence.

Objet : collecte, hébergement, organisation, assistance IA, traduction éventuelle, génération, signature, remise et export des états des lieux. Durée : contrat et phases de restitution/suppression documentées.

Personnes : locataires, bailleurs, mandataires, collaborateurs de l'agence et signataires. Données : identités, coordonnées nécessaires, qualité et pouvoir, adresse du logement, observations, photographies, relevés, clés, signatures et traces de preuve. Limiter les données sans rapport avec le constat, les documents privés et les personnes photographiées.

## 2. Instructions et engagements

L'agence documente ses instructions, sa base légale, l'information des personnes et les habilitations. Tenu :
- traite uniquement sur instructions documentées, y compris pour les transferts, sauf obligation légale avec information préalable lorsque permise ;
- alerte immédiatement si une instruction lui paraît contraire au droit de la protection des données ;
- impose la confidentialité aux personnes autorisées ;
- met en œuvre les mesures adaptées à l'article 32, décrites et vérifiées dans l'annexe technique ;
- aide l'agence à traiter les droits, la sécurité, les violations, analyses d'impact et consultations préalables ;
- communique les informations nécessaires pour démontrer la conformité et permet les audits, avec modalités proportionnées qui ne neutralisent pas ce droit ;
- restitue ou supprime les données au choix de l'agence en fin de prestation, sauf conservation légalement requise.

## 3. Prestataires et transferts

Autorisation générale proposée des sous-traitants ultérieurs inscrits dans une liste acceptée. Chaque ligne précise : entité juridique, fonction, données, lieux de stockage et d'accès, durée, garanties et mécanisme de transfert le cas échéant.

Liste réelle À compléter : hébergeur/base de données, stockage photo, fournisseur IA, signature, messagerie, support et sauvegardes. Les anciennes listes Make/Tally/Airtable ne sont pas une cartographie vérifiée de l'architecture actuelle.

Notification des ajouts/remplacements au moins 30 jours à l'avance, avec faculté d'objection motivée et recherche d'une solution ; si aucune solution n'est possible, prévoir la sortie du service concerné et ses effets financiers. Les obligations pertinentes sont répercutées aux prestataires ; Tenu reste responsable envers l'agence de leur exécution selon l'article 28.

Tout accès hors EEE fait l'objet d'une qualification et de garanties documentées si requises. Vérifier les conditions des API IA, la rétention et l'absence d'entraînement ; aucune promesse de résidence européenne intégrale sans preuve.

## 4. Mesures de sécurité à vérifier avant engagement

| Mesure | Preuve attendue |
|---|---|
| Séparation des agences et des rôles | Tests d'accès croisés, y compris liens photo et exports |
| Comptes individuels et authentification renforcée des administrateurs | Configuration et procédure d'habilitation/révocation |
| Chiffrement en transit et au repos | Configurations et gestion des clés |
| Stockage privé et liens temporaires | Tests d'accès et durée d'expiration documentée |
| Signature et intégrité | Dossier de preuve, version signée et annexes liées |
| Remise à chaque partie | Journaux, traitement des erreurs et remise alternative |
| Sauvegarde et restauration | Test de restauration, fréquence et objectifs À compléter |
| Journalisation et accès support | Traces protégées, durées et accès limité |
| Gestion des vulnérabilités et incidents | Procédures, contacts et exercices |
| Effacement et réversibilité | Tests couvrant bases, fichiers, prestataires et sauvegardes |

Ces mesures sont des exigences à confirmer, pas la description d'une conformité acquise.

## 5. Violations et droits

Tenu notifie une violation à l'agence sans délai indu après en avoir connaissance, avec les informations disponibles puis les compléments : faits, données et personnes concernées, conséquences, mesures et contact. Objectif contractuel proposé : première alerte sous 24 heures, à valider opérationnellement ; ce délai ne permet pas de retarder une alerte disponible plus tôt.

L'agence évalue ses obligations de notification aux autorités et personnes ; l'ensemble des violations n'entraîne pas automatiquement une notification à la CNIL. Tenu coopère et conserve les traces utiles. Les demandes de droits reçues directement sont transmises sans délai à l'agence, sauf traitement relevant de la responsabilité propre de Tenu.

## 6. Conservation et sortie

| Catégorie | Règle à définir avant données réelles |
|---|---|
| Brouillons et fichiers inutilisés | Durée courte justifiée et purge automatisée |
| États des lieux signés, photos annexées et preuve | Durée proportionnée à la relation locative et aux besoins probatoires, validée juridiquement |
| Journaux techniques | Durée distincte selon finalité et minimisation |
| Données commerciales/comptables propres à Tenu | Obligations et durées distinctes documentées |
| Sauvegardes | Cycle d'expiration et absence de réactivation des données supprimées |
| Contentieux | Gel ciblé, accès restreint, motif et revue périodique |

Aucune durée légale unique n'est postulée pour toutes ces catégories. Ne pas appliquer une suppression photo à 30 jours aux annexes probatoires sans analyse.

Proposition de sortie : 90 jours de lecture/export inclus, puis restitution/suppression selon instruction et calendrier validé, avec attestation sur demande. Toute conservation obligatoire est isolée, motivée et limitée. Le calendrier couvre les prestataires et les sauvegardes.

## 7. Éléments à signer

Annexer les identités et contacts, instructions, tableau des traitements, durées, liste réelle des prestataires/transferts, mesures techniques vérifiées, procédure incident, modalités d'audit et formats d'export.

Sources : [RGPD, chapitre IV / CNIL](https://cnil.fr/fr/reglement-europeen-protection-donnees/chapitre4), [clauses article 28 / CNIL](https://www.cnil.fr/fr/clauses-contractuelles-types-entre-responsable-de-traitement-et-sous-traitant).
