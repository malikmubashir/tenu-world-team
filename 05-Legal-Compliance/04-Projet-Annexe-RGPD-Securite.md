# Tenu — Projet d'annexe RGPD et sécurité

28 octobre 2026 — Trame à compléter et contractualiser avant tout pilote contenant des données réelles.  
Ce document ne certifie pas l'état technique du service.


## Précisions du responsable juridique — 29 octobre 2026

**Stockage :** les photos sont stockées chiffrées chez Cloudflare dans l'Union européenne, selon les informations communiquées par le responsable juridique. Cette précision est intégrée au cadre documentaire ; la configuration, l'entité Cloudflare contractante, la région effective, la gestion des clés, les accès de support et les garanties de transfert restent à documenter dans la cartographie technique. Le chiffrement du stockage ne doit pas être présenté comme du chiffrement de bout en bout sans dispositif correspondant.

**Interdiction d'entraînement :** les photos et leurs copies ne sont jamais utilisées pour entraîner ou affiner des modèles d'intelligence artificielle, par Tenu ou par ses prestataires. Cette interdiction est contractuelle et doit être répercutée dans le choix, les conditions et les réglages des API IA. Leur analyse pour générer les constats relève de l'inférence, avec rétention temporaire limitée ; elle n'autorise aucun entraînement. Aucune dérogation d'entraînement n'est prévue par cette offre.

**Purge à douze mois :** les fichiers photo séparés d'entrée et de sortie sont supprimés de la production douze mois après la date effective de sortie du locataire, renseignée et vérifiée par l'agence. Le délai ne court ni depuis le téléversement ni depuis la signature du constat d'entrée. Les photos intégrées aux PDF signés ne sont pas concernées par cette purge : les PDF et leurs éléments de preuve suivent leur calendrier documentaire propre, sans retrait ni altération des images. Les fichiers inutilisés et copies temporaires peuvent être supprimés plus tôt selon les délais dédiés. Les sauvegardes expirent selon leur cycle documenté, sans réactivation après restauration ; un gel contentieux ciblé ou une obligation légale peut suspendre une purge, avec motif, accès restreint et revue périodique. L'information des personnes doit distinguer explicitement suppression des fichiers séparés et maintien des images dans les PDF. La fin du service reste régie par la restitution/suppression, et n'impose pas une conservation par Tenu jusqu'à cette échéance.

**Grille de vétusté :** référence retenue : [article 4 du décret n° 2016-382 du 30 mars 2016](https://www.legifrance.gouv.fr/loda/article_lc/LEGIARTI000032324427). Le décret encadre la prise en compte de la vétusté et le choix d'une grille issue d'un accord collectif ; il ne fournit pas une grille nationale chiffrée unique. Renseigner dans chaque dossier la grille retenue, sa version, l'accord collectif source et son acceptation par les parties au bail. Une grille interne non justifiée ne doit pas être présentée comme réglementaire. L'IA ne choisit pas seule la grille et ne décide pas de l'imputabilité ou d'une retenue.

## 1. Qualification et description

Le prestataire Tenu est Global Apex.Net, exploitant de Tenu.World, identifié dans les [conditions d'abonnement](03-Projet-Conditions-Abonnement-B2B.md). Source d'identité et contacts : [CGU publiées v1.1 du 12 juin 2026](https://tenu.world/legal/terms/fr), consultées le 29 octobre 2026. Contact données et droits : dpo@tenu.world ; assistance générale : support@tenu.world.

Pour les dossiers d'états des lieux, la qualité de Global Apex.Net résulte de l'analyse des instructions et finalités ci-dessous. Pour sa gestion commerciale, ses comptes, sa facturation et ses obligations propres, Global Apex.Net agit comme responsable distinct. L'ancienne qualification de responsable figurant sur le site ne doit pas être étendue automatiquement à tous les dossiers traités pour les agences. Les droits des personnes concernent les personnes physiques (locataires, bailleurs, signataires et collaborateurs), pas seulement l'agence personne morale.

Global Apex.Net relaie à l'agence les demandes relatives aux données traitées pour son compte et répond aux demandes relatives à ses propres finalités. Les bases et durées sont précisées par traitement ; la seule existence d'un contrat avec une agence ne suffit pas à justifier tous les traitements de personnes tierces. L'information des participants et l'annexe article 28 doivent être cohérentes.

Les noms de prestataires évoqués dans les anciennes CGU ne constituent pas une liste technique validée. Confirmer entités, contrats et configurations ; aucune fonction de non-entraînement chez un fournisseur n'est présumée activée du seul fait de sa mention sur le site.


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

Les [compléments confidentialité et remboursements B2B](07-Confidentialite-Remboursements-B2B.md), section 2, analysent la source confidentialité du dépôt, consultée le 29 octobre 2026. La version déployée n'a pas pu être lue directement. Les déclarations de cette source restent à confirmer techniquement et contractuellement :

| Prestataire mentionné | Fonction / localisation annoncée dans la source | Vérification requise |
|---|---|---|
| Supabase | Base/authentification, Francfort | Entité, région et accès support |
| Cloudflare R2 | Photos/PDF, UE | Chiffrement, région, clés et cycle de purge |
| Vercel | Hébergement web, Paris | Données des logs et traitements hors région |
| Brevo | Courriels, France | Entité contractante, données et rétention |
| Stripe | Paiement, entité européenne annoncée | Rôle par finalité, flux et métadonnées |
| Anthropic API | Analyse, traitement aux États-Unis | Offre, rétention, absence d'entraînement, DPA et garanties de transfert |

Cette liste déclarative complète la cartographie à établir ; elle ne certifie ni DPA signé, ni résidence intégrale UE, ni certification à jour. La migration IA évoquée dans la source est un projet, pas un déploiement constaté. La résidence UE des photos ne suffit pas à qualifier le lieu d'inférence. Ne pas promettre de zéro rétention sans engagement prouvé.


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
| PDF signés contenant les photos et dossier de preuve | Calendrier documentaire propre : usage actif puis archivage restreint selon mandat et clôture des comptes | Les photos intégrées restent dans le PDF ; elles ne sont pas supprimées à douze mois |
| Journaux techniques | Durée distincte selon finalité et minimisation |
| Données commerciales/comptables propres à Tenu | Obligations et durées distinctes documentées |
| Sauvegardes | Cycle d'expiration et absence de réactivation des données supprimées |
| Contentieux | Gel ciblé, accès restreint, motif et revue périodique |

La règle de douze mois après sortie concerne uniquement les fichiers photo séparés. Aucune durée légale unique n'est postulée pour toutes ces catégories. Ne pas appliquer une suppression photo à 30 jours aux annexes probatoires sans analyse.

Proposition de sortie : 90 jours de lecture/export inclus, puis restitution/suppression selon instruction et calendrier validé, avec attestation sur demande. Toute conservation obligatoire est isolée, motivée et limitée. Le calendrier couvre les prestataires et les sauvegardes.

### 6.1 Politique proposée pour les photographies

Les délais ci-dessous sont des propositions opérationnelles à valider juridiquement et techniquement avec l'agence avant collecte ; ils ne sont pas présentés comme des durées légales obligatoires. Une fois validés, ils sont inscrits dans les instructions et l'information des participants.

| Catégorie | Durée/événement proposé | Garde-fou |
|---|---|---|
| Photos rejetées, floues, doublons et non retenues | Purge sous 30 jours après signature/clôture du dossier | Vérifier qu'elles ne sont ni annexées ni nécessaires à une réserve ou un litige ; la clôture d'entrée ne supprime jamais les photos retenues pour la comparaison de sortie |
| Brouillons abandonnés, non signés | Alerte après 60 jours sans activité ; purge à 90 jours sans activité | Agence avertie, report motivé et borné ; un refus de signature/litige ne vaut pas abandon |
| Copies de traitement IA, conversion et caches de travail | Suppression à la fin du traitement, cible maximale 7 jours | Valider les contraintes des fournisseurs ; distinguer des journaux de sécurité et des pièces probatoires |
| Fichiers photo séparés retenus, y compris originaux autonomes | Conservation pour l'entrée/sortie puis purge en production douze mois après sortie effective du locataire | Date vérifiée par l'agence ; exceptions ciblées légales/contentieuses ; pas de prolongation automatique jusqu'à la clôture des comptes |
| Copies de sauvegarde des données supprimées | Expiration selon cycle technique documenté, cible maximale 90 jours après suppression en production | Pas d'accès courant ; rejouer les suppressions avant remise en service après restauration |
| Pièces faisant l'objet d'un gel pour litige | Conservation ciblée jusqu'à décision documentée de levée du gel, puis réapplication du calendrier | Revue au moins semestrielle ; pas de prolongation indéfinie de tout le dossier |

Le délai de trois ans des actions dérivant du bail prévu à l'article 7-1 court à partir de la connaissance des faits ; il ne constitue donc pas une obligation générale de conservation de trois ans après départ. Le référentiel CNIL de gestion locative distingue notamment la gestion déléguée et prévoit des repères allant jusqu'à cinq ans en archivage intermédiaire. Le régime et la clôture des comptes doivent être documentés ; ces repères ne justifient pas la conservation systématique de toutes les photos. La fin de l'abonnement n'autorise pas Tenu à garder tous les dossiers pour cette durée : la restitution/suppression de l'article 28 s'applique, sauf instruction contractuelle de conservation justifiée ou obligation légale propre.

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


### 6.4 Complément de paramétrage

Les [paramètres proposés pour les quatre volets](06-Parametres-Conservation-Signature-Service-Assurance.md), section 1, précisent les instructions proposées : logs courants 6 mois, dates et alertes, maintien des pièces d'entrée pour la sortie, archivage restreint, fin d'abonnement et contrôle des sauvegardes. Cette proposition corrige l'hypothèse initiale uniforme de trois ans après fin du bail. Les délais restent soumis à validation et information des personnes avant collecte. Les paramètres de service et de signature du même document doivent être validés avant tout engagement chiffré.

### 6.5 Information, droits et cohérence avec la politique publique

Les [compléments confidentialité et remboursements B2B](07-Confidentialite-Remboursements-B2B.md), section 2, précisent les points à reprendre dans l'information des participants : rôles séparés, absence de consentement universel, données potentiellement sensibles dans les photos, droits applicables, identité proportionnée, cookies et notification des violations selon le risque.

L'ancien délai de 24 mois de la source confidentialité ne remplace pas les décisions validées ici : fichiers photo séparés purgés douze mois après sortie effective et PDF signés préservés selon leur calendrier propre. La fermeture d'un compte ne modifie pas silencieusement un acte signé.

## 7. Éléments à signer

Annexer les identités et contacts, instructions, tableau des traitements, durées, liste réelle des prestataires/transferts, mesures techniques vérifiées, procédure incident, modalités d'audit et formats d'export.

Sources : [RGPD, chapitre IV / CNIL](https://cnil.fr/fr/reglement-europeen-protection-donnees/chapitre4), [clauses article 28 / CNIL](https://www.cnil.fr/fr/clauses-contractuelles-types-entre-responsable-de-traitement-et-sous-traitant).
