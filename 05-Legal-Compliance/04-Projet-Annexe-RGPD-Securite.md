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

### 6.1 Politique proposée pour les photographies

Les délais ci-dessous sont des propositions opérationnelles à valider juridiquement et techniquement avec l'agence avant collecte ; ils ne sont pas présentés comme des durées légales obligatoires. Une fois validés, ils sont inscrits dans les instructions et l'information des participants.

| Catégorie | Durée/événement proposé | Garde-fou |
|---|---|---|
| Photos rejetées, floues, doublons et non retenues | Purge sous 30 jours après signature/clôture du dossier | Vérifier qu'elles ne sont ni annexées ni nécessaires à une réserve ou un litige ; la clôture d'entrée ne supprime jamais les photos retenues pour la comparaison de sortie |
| Brouillons abandonnés, non signés | Alerte après 60 jours sans activité ; purge à 90 jours sans activité | Agence avertie, report motivé et borné ; un refus de signature/litige ne vaut pas abandon |
| Copies de traitement IA, conversion et caches de travail | Suppression à la fin du traitement, cible maximale 7 jours | Valider les contraintes des fournisseurs ; distinguer des journaux de sécurité et des pièces probatoires |
| Images retenues dans les états des lieux, originaux nécessaires et preuve | Usage actif pendant le bail ; proposition d'archivage intermédiaire restreint pendant 3 ans à compter de la fin du bail | Point de départ et durée à valider selon droits concernés, connaissance des faits, interruptions/suspensions et autres recours ; aucune purge automatique fondée sur cette seule hypothèse sans validation |
| Copies de sauvegarde des données supprimées | Expiration selon cycle technique documenté, cible maximale 90 jours après suppression en production | Pas d'accès courant ; rejouer les suppressions avant remise en service après restauration |
| Pièces faisant l'objet d'un gel pour litige | Conservation ciblée jusqu'à décision documentée de levée du gel, puis réapplication du calendrier | Revue au moins semestrielle ; pas de prolongation indéfinie de tout le dossier |

Le délai de trois ans des actions dérivant du bail prévu à l'article 7-1 court à partir de la connaissance des faits ; il ne constitue donc pas une obligation générale de conservation de trois ans après départ. L'hypothèse proposée doit être adaptée et validée. La fin de l'abonnement n'autorise pas Tenu à garder tous les dossiers pour cette durée : la restitution/suppression de l'article 28 s'applique, sauf instruction contractuelle de conservation justifiée ou obligation légale propre.

### 6.2 Procédure de purge et contrôle

1. Identifier le dossier, la phase entrée/sortie, la catégorie, les supports, la date de départ et l'échéance ; référencer les images utilisées dans un document signé.
2. Vérifier l'instruction, les droits des personnes, les besoins de comparaison, les contentieux et tout gel en cours. Aucun effacement automatique d'une annexe signée du seul fait de la génération du PDF.
3. Avertir l'agence avant purge définitive d'un dossier probatoire ou abandonné et permettre l'export dans les délais convenus. Le silence ne crée pas un nouveau motif de conservation illimitée.
4. Purger bases, objets et versions de stockage, miniatures, caches, index, appareils gérés et prestataires concernés ; révoquer les liens. Les obligations de suppression des copies sur appareils de l'agence sont précisées avec elle.
5. Pour une image intégrée au PDF signé, appliquer la décision au document et au dossier complet selon le calendrier : ne pas retirer silencieusement l'image d'un exemplaire signé. Une rectification se fait par complément traçable.
6. Consigner les identifiants minimaux des objets supprimés, la règle appliquée, date, opérateur/job, statut et exceptions sans dupliquer les photos dans les logs. Fixer séparément la durée de ces logs.
7. Suivre les échecs, obtenir les confirmations utiles des prestataires et vérifier l'expiration des sauvegardes. Distinguer suppression en production et effacement complet ; ne pas certifier le second prématurément.

Les copies déjà remises aux bailleurs, locataires ou exportées par l'agence ne sont pas effaçables à distance par Tenu ; leurs détenteurs restent soumis aux obligations qui leur sont applicables.

### 6.3 Sources de la politique

- [CNIL — durées de conservation](https://www.cnil.fr/fr/passer-laction/les-durees-de-conservation-des-donnees) : finalité, conservation active et archivage restreint.
- [CNIL — sauvegardes](https://www.cnil.fr/fr/securite-sauvegarder).
- [Loi du 6 juillet 1989, article 7-1](https://www.legifrance.gouv.fr/loda/id/JORFTEXT000000509310/) : prescription des actions dérivant du bail, à distinguer d'une durée de conservation.


## 7. Éléments à signer

Annexer les identités et contacts, instructions, tableau des traitements, durées, liste réelle des prestataires/transferts, mesures techniques vérifiées, procédure incident, modalités d'audit et formats d'export.

Sources : [RGPD, chapitre IV / CNIL](https://cnil.fr/fr/reglement-europeen-protection-donnees/chapitre4), [clauses article 28 / CNIL](https://www.cnil.fr/fr/clauses-contractuelles-types-entre-responsable-de-traitement-et-sous-traitant).
