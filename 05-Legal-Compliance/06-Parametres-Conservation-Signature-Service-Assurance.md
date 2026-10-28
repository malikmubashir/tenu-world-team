# Tenu — Paramètres proposés : conservation, signature, service et assurance

28 octobre 2026 — Version de travail 1.0  
Statut : proposition pour validation du responsable juridique et des responsables techniques. Les modalités commerciales d'abonnement restent celles déjà retenues. Les paramètres ci-dessous ne constituent pas une attestation de conformité ou de couverture ni un SLA déjà souscrit. Prestataire de signature et assureur : **À confirmer**, conformément à l'instruction du responsable juridique.

## 1. Conservation et purge

### 1.1 Dossiers signés et photographies retenues

Proposition : conserver les états des lieux d'entrée/sortie, annexes photographiques, originaux nécessaires et dossier de preuve pendant la location et jusqu'à clôture des comptes locatifs. Après cette phase, passer en archivage intermédiaire à accès restreint, sans réutilisation commerciale ni entraînement IA.

Pour les agences agissant en gestion déléguée, retenir comme paramètre proposé **cinq ans après clôture des comptes locatifs**, sous réserve d'une analyse documentée du mandat et des besoins probatoires. Dans une gestion directe ou semi-déléguée, examiner **trois ou cinq ans selon la répartition des tâches** ; ne pas déduire la durée du seul statut d'agence.

La documentation précédente proposait trois ans après fin du bail comme hypothèse générale. La présente proposition la précise à partir du référentiel CNIL de gestion locative : le régime de gestion et la clôture des comptes doivent être renseignés. Il ne s'agit pas d'une obligation légale uniforme de garder toutes les photos cinq ans.

Ne conserver avec le signé que les images retenues et les originaux effectivement nécessaires. Les photos d'entrée restent disponibles pour établir la sortie. Le document signé et ses annexes ne sont pas modifiés pour retirer une image ; toute rectification est traitée par complément traçable.

Le dossier doit porter : date de fin du bail, date de clôture des comptes, régime de gestion, catégorie de document, instruction applicable et date de purge. Si une date manque, déclencher une alerte mensuelle et une revue humaine sous 30 jours ; aucune purge aveugle ni conservation indéfinie faute de renseignement. L'agence documente aussi le cas où des comptes restent ouverts anormalement longtemps.

### 1.2 Autres copies et catégories

| Catégorie | Paramètre proposé | Point de départ et contrôle |
|---|---|---|
| Photos rejetées/non retenues | 30 jours maximum | Signature ou clôture du constat ; vérifier absence de réserve/litige nécessitant l'image |
| Dossiers abandonnés non signés | Alerte à 60 jours, purge à 90 jours | Dernière activité ; un désaccord ou refus de signature ne vaut pas abandon |
| Copies temporaires IA/conversion | Suppression en fin de traitement, maximum 7 jours | Fin de l'opération ; vérifier les engagements effectifs du fournisseur |
| Logs techniques courants | 6 mois | Événement ; minimiser le contenu et exclure photos/prompts complets ; traces probatoires isolées dans le dossier signé |
| Sauvegardes | Cycle d'expiration maximum 90 jours | Suppression en production ; données isolées, sans usage courant ; rejeu des suppressions avant restauration en production |
| Gel contentieux | Durée nécessaire au litige et aux recours applicables | Décision motivée, pièces ciblées, revue au moins semestrielle et levée documentée |

Ces délais courts sont des choix proposés pour Tenu, non des durées imposées par la CNIL. Les données de facturation suivent leur propre calendrier légal et ne justifient pas la conservation de toutes les photos.

### 1.3 Fin de l'abonnement, du pilote ou du mandat

Proposition : lecture/export pendant 90 jours après fin du service, avec avertissements à J+60 et J+80. Ne pas assimiler cette fenêtre à un service d'archivage de cinq ans. L'agence récupère PDF signés, photos/annexes, originaux utiles, inventaire et preuves de signature/remise.

À l'issue, exécuter les instructions de restitution/suppression, sauf conservation légalement requise. Une conservation assurée par Tenu au-delà nécessite une instruction et une prestation d'archivage définies contractuellement, y compris coûts et réversibilité. Le gel demandé par l'agence ne crée pas à lui seul une prestation gratuite d'archivage illimitée.

L'attestation de purge distingue la production supprimée et les sauvegardes encore en cycle d'expiration. La purge couvre aussi versions d'objets, miniatures, prestataires et appareils gérés. Les exemplaires déjà remis aux parties ou exportés ne peuvent pas être effacés à distance par Tenu.

### 1.4 Clause proposée

« L'Agence fixe dans ses instructions les durées applicables en fonction de sa mission et informe les personnes concernées. Tenu conserve les pièces du dossier signé et les photographies nécessaires selon ce calendrier, puis les archive avec accès restreint ou les supprime à l'échéance. Les documents faisant l'objet d'un contentieux sont isolés et conservés sur instruction motivée pour la durée nécessaire. La fin de l'abonnement déclenche la procédure de réversibilité ; elle n'emporte ni destruction immédiate des preuves ni engagement implicite d'archivage illimité. »

## 2. Signature électronique et remise

### 2.1 Niveau proposé

Cible recommandée pour ce produit : **signature électronique avancée au sens d'eIDAS**, sous réserve d'analyse de risque et de vérification du service choisi. Ce choix est une recommandation de conception, pas l'affirmation d'une obligation générale de signature avancée pour les états des lieux. Un niveau qualifié peut être envisagé si les risques le justifient.

Un code SMS ou une signature dessinée ne suffisent pas à eux seuls à qualifier le procédé d'« avancé ». Vérifier notamment identification, lien au signataire, contrôle de ses moyens de signature et détection des modifications. La présomption légale de fiabilité applicable à un procédé qualifié ne doit pas être revendiquée pour une simple collecte d'OTP.

Prestataire, offre exacte, niveau démontré, implantation des données, coûts et conditions de conservation : **À confirmer**. La qualification éventuelle d'un prestataire ne prouve pas que toutes ses offres et tous les parcours Tenu sont qualifiés.

### 2.2 Parcours requis

1. Identifier chaque signataire et sa qualité ; vérifier le mandat de l'agence. Prévoir une procédure proportionnée pour signataires étrangers et numéros internationaux. Ne pas conserver systématiquement des copies de pièces d'identité sans nécessité.
2. Présenter le document complet en français et les traductions explicatives identifiées ; laisser corriger les constats et inscrire les réserves avant validation.
3. Figer rapport, inventaire et photos annexées dans une enveloppe de signature. Toute modification pendant la collecte des signatures invalide l'enveloppe courante et déclenche une nouvelle validation de tous.
4. Obtenir l'action personnelle de chaque signataire via le moyen vérifié prévu au dispositif ; ne pas laisser l'agent signer à la place d'un locataire.
5. Générer le PDF signé et son dossier de preuve : empreinte, identifiants de versions, horodatages, éléments d'identification/consentement nécessaires, validation et statut des signatures.
6. Remettre le dossier complet à chaque partie/mandataire au moment de la signature. Un lien seul n'est acceptable que si la remise durable est effectivement assurée ; ne pas laisser les photos dépendre d'une URL expirante.
7. Conserver preuves de remise et traitement des échecs ; si la remise dématérialisée échoue, organiser une remise alternative sans considérer le dossier comme complètement remis.

En cas de refus, d'identité incertaine ou de panne, ne pas produire de statut « signé ». Prévoir un état des lieux papier contradictoire de secours et sa remise ; la numérisation ultérieure n'est pas présentée comme l'original électronique signé. En cas d'impossibilité amiable, orienter vers le régime légal applicable.

### 2.3 Clause proposée

« La signature porte sur la version finale du rapport et les annexes photographiques identifiées. Chaque signataire doit pouvoir en prendre connaissance, demander une correction et exprimer ses réserves avant signature. Tenu conserve les éléments de preuve du parcours et permet leur export. Le document signé ne fait l'objet d'aucune modification silencieuse. Une correction postérieure est identifiée comme complément, sans suppression de l'original. »

### 2.4 Recette avant données réelles

Tests : deux signataires avec réserves, mandataire, numéro étranger, modification entre deux signatures, OTP perdu/erreur, refus, doublon, panne, signature asynchrone, compléments, export et validation de l'intégrité du PDF/annexes. Obtenir du fournisseur un dossier de preuve d'exemple et une description du niveau eIDAS de l'offre exacte.

## 3. Annexe de service proposée

Les chiffres ci-dessous sont des **objectifs à soumettre à la validation technique et budgétaire**. Ils ne doivent être promis au client qu'une fois mesurables et acceptés au bon de commande. Ils ne sont pas des standards réglementaires.

### 3.1 Disponibilité et assistance

| Paramètre | Proposition |
|---|---|
| Disponibilité | 99,5 % par mois civil, mesure 24 h/24 |
| Services mesurés | Authentification, accès dossiers/photos, enregistrement, génération, signature et remise ; une dépendance fournisseur bloquante compte comme indisponibilité |
| Assistance | Lundi–vendredi, 9 h–18 h, heure de Paris, hors jours fériés français ; pas d'astreinte implicite le soir/week-end |
| Canal | Portail et adresse de support À confirmer ; ticket horodaté |
| Maintenance planifiée | Préavis de 48 h, hors plage de support si possible ; maximum 2 h exclues du calcul par mois |
| Maintenance urgente | Information dès que possible ; comptée dans l'indisponibilité |
| Suivi | Tableau de disponibilité et rapport d'incident majeur ; méthode de mesure documentée |

Calcul : disponibilité = 1 − minutes d'indisponibilité / minutes de service éligibles. Les minutes de service éligibles sont les minutes du mois moins la maintenance planifiée conforme dans la limite de 2 h ; au-delà, la maintenance compte comme indisponibilité. Les incidents imputables exclusivement au terminal/réseau de l'agence sont exclus sur justification ; ne pas exclure globalement les prestataires choisis par Tenu.

À 99,5 %, le budget d'indisponibilité représente environ 3 h 36 pour un mois de 30 jours hors exclusions. Cet objectif ne garantit pas la disponibilité à l'heure d'un rendez-vous : le secours opérationnel reste indispensable.

### 3.2 Incidents

| Priorité | Exemple | Prise en charge humaine cible | Objectif de contournement/rétablissement |
|---|---|---|---|
| P1 critique | Dossiers indisponibles pour toutes les agences, perte suspectée, signature/remise bloquée globalement | 2 heures ouvrées | 1 jour ouvré |
| P2 majeure | Fonction essentielle dégradée pour une agence sans contournement satisfaisant | 4 heures ouvrées | 2 jours ouvrés |
| P3 normale | Anomalie non bloquante | 1 jour ouvré | Planification communiquée sous 5 jours ouvrés |

Les délais ouvrés courent dans la plage de support. Accusé automatique distinct de la prise en charge humaine. Les délais de résolution sont des objectifs de service, sans garantie de correction de toute anomalie dans ce délai. Les obligations RGPD de notification sans délai indu ne sont pas suspendues en dehors des horaires de support ; un contact d'urgence sécurité réellement surveillé doit être défini avant données réelles.

### 3.3 Sauvegarde et reprise

Cibles proposées : **RPO d'une heure** (perte de données maximale visée en cas de sinistre) et **RTO d'un jour ouvré** (reprise visée), à tester sur base, photos, annexes et preuve de signature. Choisir une stratégie cohérente avec ces objectifs ; une seule sauvegarde quotidienne ne suffit pas à démontrer un RPO d'une heure.

Un dossier n'est annoncé « enregistré/signé et remis » qu'après confirmation des écritures durables et du parcours effectif. Le RPO cible n'autorise pas une suppression volontaire d'actes signés. Sauvegardes protégées, séparées de la production, accès restreints, restauration testée au moins trimestriellement et après changement majeur. Éviter de restaurer le document sans ses photos ou preuves.

### 3.4 Recours proposés

Si le SLA devient contractuel : proposition d'avoir sur la mensualité HT de base du mois affecté, 5 % si disponibilité inférieure à 99,5 %, 10 % sous 99 %, 20 % sous 98 %, plafonné à 20 %. Pas de cumul des paliers. L'avoir ne constitue pas une exclusion des responsabilités légalement applicables ni des autres droits contractuels.

Prévoir une faculté de résiliation sans mensualités futures d'engagement si la disponibilité est inférieure à 99 % durant deux mois consécutifs ou trois mois sur six, après notification documentée et examen contradictoire des mesures. Cette clause reste à valider commercialement et juridiquement avec le régime général de manquement.

### 3.5 Réversibilité et preuve de capacité

Export autonome PDF signés, annexes/photos, originaux nécessaires, inventaire et preuves. Lecture/export proposé pendant 90 jours après fin. Avant de promettre ce service : démontrer export complet, restauration, mesure de disponibilité, alertes et couverture de l'assistance. Distinguer archivage intermédiaire de preuve et sauvegarde de reprise.

## 4. Assurance et responsabilité

### 4.1 Risques à présenter au courtier

Décrire exactement : éditeur SaaS pour agences en France, états des lieux signés, photos d'intérieurs, descriptions/comparaisons IA, traductions pour expatriés, prestataires externes, risques de perte/altération de preuve et absence de garantie de résultat locatif.

Demander :
- RC professionnelle éditeur logiciel/SaaS couvrant erreurs, omissions et défauts du service, dommages immatériels et frais de défense ;
- confirmation écrite du traitement des erreurs IA, de traduction, du parcours de signature et des préjudices liés à une preuve inexploitable ;
- couverture cyber pour réponse à incident, expertise, notification et restauration, avec examen de l'interruption d'activité et de la responsabilité données ;
- examen des exclusions IA/conseil juridique/immobilier, défaut de sauvegarde, prestataires, obligations contractuelles et territoires ; adéquation des sous-limites et franchises ;
- confirmation de la couverture des pilotes comportant de vrais dossiers, date d'effet, fait générateur, rétroactivité et garantie subséquente selon le contrat.

Ne pas confondre l'assurance de l'agence immobilière et celle de l'éditeur Tenu. L'assurance ne finance pas automatiquement les avoirs SLA ni les amendes ; vérifier leur assurabilité et les exclusions.

### 4.2 Budget de couverture à soumettre au courtier

Point de départ de consultation proposé, sans affirmation de prix de marché ni de disponibilité :
- RC Pro : 1 000 000 € par sinistre et par année d'assurance ;
- cyber : 500 000 € par sinistre et par année ;
- franchises et sous-limites : À confirmer selon trésorerie et exposition.

Ces montants sont des objectifs de consultation à ajuster selon nombre d'agences, volume, risque de sinistre collectif et devis. Aucune attestation ni couverture effective n'est déduite de ce document.

### 4.3 Clause d'assurance proposée

« Tenu maintient pendant la fourniture du service une assurance de responsabilité professionnelle adaptée à son activité d'éditeur SaaS et aux fonctionnalités déclarées. Les coordonnées de l'assureur, la police, les garanties, plafonds, franchises et exclusions pertinentes sont renseignés avant signature du contrat définitif. Une attestation à jour peut être fournie à l'Agence. Toute modification substantielle affectant la couverture de la prestation est portée à sa connaissance. »

Cette rédaction est conditionnée à la souscription effective ; ne pas l'insérer comme affirmation d'une assurance déjà active.

### 4.4 Responsabilité

Conserver une responsabilité propre de Tenu pour logiciel, sécurité, conservation et remise convenues, et celle de l'agence pour mandats, accès et vérification des constats. Le plafond contractuel de responsabilité reste À confirmer après analyse juridique et assurance ; il ne se confond pas avec le plafond de police. Ne pas retenir mécaniquement douze mois de petites mensualités face au risque de perte de preuve, ni exonérer globalement les erreurs IA.

## 5. Tableau de clôture des quatre sujets

| Sujet | Proposition rédigée | Preuves/validation restant nécessaires |
|---|---|---|
| Conservation | Calendrier, gestion déléguée/directe, purge et gel | Validation agence/juridique, instruction article 28, tests de purge et d'export |
| Signature | Niveau avancé cible, parcours, secours et recette | Prestataire/offre À confirmer, niveau démontré, preuve de recette |
| Service | SLA chiffré proposé, horaires, incidents, RPO/RTO, recours | Validation technique/budget, mesures et tests avant engagement |
| Assurance | Activités, garanties, clause et montants de consultation | Assureur/police À confirmer, garanties écrites et couverture effective |

## 6. Sources officielles consultées le 28 octobre 2026

- [CNIL — référentiel de gestion locative, section 8](https://www.cnil.fr/sites/cnil/files/atoms/files/referentiel_relatif_aux_traitements_de_donnees_personnelles_mis_en_oeuvre_dans_le_cadre_de_la_gestion_locative.pdf) : repères différenciés de conservation selon phase et gestion ; ne pas transformer ces repères en obligation uniforme pour chaque image.
- [CNIL — conservation](https://www.cnil.fr/fr/passer-laction/les-durees-de-conservation-des-donnees).
- [Code civil, article 1367](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000032042456/) : identification, consentement et lien à l'acte.
- [ANSSI — sélection du niveau des signatures](https://cyber.gouv.fr/reglementation/reglementation-identite-confiance-numerique/securite-echanges-voie-electronique/reglement-eidas/selection-niveau-signatures-cachets-%C3%A9lectroniques/) : analyse du risque et niveaux de signature.
- [Cadre B2B](02-Cadre-B2B-Agences-France.md), [conditions](03-Projet-Conditions-Abonnement-B2B.md), [annexe RGPD](04-Projet-Annexe-RGPD-Securite.md).
