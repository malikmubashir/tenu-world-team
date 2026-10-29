# Tenu — Compléments confidentialité et remboursements B2B

29 octobre 2026 — Projet à valider avant publication. Ce document complète les conditions d'abonnement et l'annexe RGPD ; il ne remplace pas leur validation et ne certifie pas les configurations techniques.

## 1. Sources et limites de vérification

Les [CGU](https://tenu.world/legal/terms/fr) ont été lues sur le site. Les pages [confidentialité](https://tenu.world/legal/privacy/fr) et [remboursement](https://tenu.world/legal/refund/fr) n'étaient pas accessibles à l'outil web lors de cette revue. Leur analyse repose sur les sources du dépôt :
- [page confidentialité](https://github.com/malikmubashir/tenu-world-team/blob/main/src/app/legal/privacy/fr/page.tsx), version déclarée v1.1 du 12 juin 2026 ;
- [page remboursement](https://github.com/malikmubashir/tenu-world-team/blob/main/src/app/legal/refund/fr/page.tsx), version déclarée v1.0 du 17 avril 2026.

La correspondance exacte avec la version actuellement déployée reste à vérifier. Les mentions d'une validation DPO ou de DPA signés dans ces sources ne constituent pas les justificatifs correspondants.

Complément d'identité déclaré dans la source confidentialité : TVA FR89 941 666 067 et APE 62.02A. À rapprocher des justificatifs actuels ; l'APE ne démontre ni une autorisation réglementaire ni une couverture d'assurance.

## 2. Confidentialité à adapter à l'offre agences

### 2.1 Rôles et information des participants

Global Apex.Net est responsable des traitements relevant de ses propres finalités (gestion commerciale, facturation, sécurité propre). Pour les états des lieux traités sur instruction de l'agence, les rôles et la chaîne de sous-traitance sont définis au cas par cas dans l'annexe article 28.

L'agence informe locataires, bailleurs et mandataires avant la collecte : finalités, bases légales, destinataires, rôle de Tenu, IA et validation humaine, durées, transferts et droits. L'abonnement d'une personne morale ne permet pas de traiter toutes les données de tiers sur le seul fondement de son exécution. Le consentement n'est pas imposé comme base unique de tous les dossiers et son retrait n'entraîne pas mécaniquement l'altération d'un acte signé.

Les photos d'intérieur peuvent révéler des données personnelles, voire des informations relevant de catégories particulières. Ne pas affirmer qu'aucune donnée sensible ne peut jamais apparaître. Prévenir les prises inutiles, limiter les accès et prévoir un traitement des captures accidentelles.

### 2.2 Conservation

Les anciens repères de 24 mois ne sont pas repris pour l'offre agences :
- fichiers photo séparés : douze mois après sortie effective du locataire, sous réserve des exceptions ciblées applicables ;
- PDF signés avec leurs images : calendrier documentaire propre et intégrité préservée ;
- copies inutilisées/temporaires, comptes, journaux et facturation : calendriers distincts justifiés, décrits dans les instructions et l'information.

Ne pas présenter suppression du fichier photo et effacement de toutes ses représentations comme équivalents. Les PDF et exemplaires déjà remis contiennent encore les photos ; l'information doit le dire. Les sauvegardes suivent leur cycle borné, avec rejouage des suppressions.

### 2.3 Prestataires et transferts

La source mentionne Supabase, Cloudflare R2, Vercel, Brevo, Stripe et Anthropic API. Cette liste sert de point de départ à la cartographie, pas de preuve de déploiement actuel.

Point majeur : stockage européen et traitement IA exclusivement européen sont deux affirmations différentes. La source décrit un traitement Anthropic aux États-Unis ; une migration prévue vers une région européenne ne doit pas être présentée comme réalisée. Vérifier l'offre exacte, les données transmises, la rétention, les accès, contrats et garanties de transfert effectivement applicables.

L'absence d'entraînement ne signifie pas absence de conservation temporaire chez le fournisseur. Interdiction d'entraînement ferme pour Tenu et ses prestataires ; une affirmation de « zéro rétention » exige une configuration et un engagement démontrés.

### 2.4 Droits, cookies et incidents

Contact données : dpo@tenu.world. La source qualifie cette adresse de point de contact ; elle ne prouve pas une désignation formelle de DPO. Réévaluer l'article 37 au regard du service et des volumes réels.

Global Apex.Net traite les demandes relevant de ses finalités et transmet sans délai à l'agence celles relevant de ses instructions. Prévoir vérification d'identité proportionnée, sans copie systématique de titre. Réponse selon les délais RGPD ; toute prolongation est motivée et notifiée dans les conditions applicables. Mentionner accès, rectification, effacement, limitation, opposition, portabilité lorsque applicable et réclamation à la CNIL.

Vérifier les cookies effectivement déposés, leurs finalités et durées. Les traceurs non exemptés restent bloqués avant consentement ; aucun consentement à un futur usage indéterminé ne suffit.

En tant que sous-traitant, Tenu alerte l'agence sans délai indu. Le responsable évalue la notification CNIL selon le risque ; elle n'est pas automatique pour chaque incident. L'information des personnes dépend notamment du risque élevé. Ne pas confondre cette procédure avec les délais d'assistance commerciale.

## 3. Politique B2B proposée de remboursement et avoirs

### 3.1 Principes

L'agence achète un accès SaaS avec engagement initial ; les anciennes règles centrées sur un rapport à l'acte ne sont pas transposées. La signature d'un état des lieux n'épuise pas l'abonnement annuel.

Le pilote n'entraîne pas de poursuite payante sans accord exprès. Les modalités financières éventuelles du pilote sont fixées au bon de commande. Les protections impératives applicables, notamment dans certaines ventes hors établissement à de petits professionnels, restent réservées. Ne pas employer une renonciation de consommateur comme mécanisme standard de souscription B2B.

### 3.2 Tableau de traitement proposé

| Situation | Traitement proposé |
|---|---|
| Abonnement commencé valablement mais peu utilisé | Pas de remboursement du seul fait de la non-utilisation, sous réserve du contrat et des droits impératifs |
| Souhait de départ pendant les 12 mois initiaux | Appliquer le régime contractuel de durée ; pas de nouvelle pénalité automatique ; sortie amiable éventuelle formalisée |
| Demande de fin après période ferme | Préavis de 30 jours ; proposition de prorata de la mensualité payée d'avance pour la période postérieure à la date effective de fin |
| Double débit ou facturation erronée | Rectification, avoir comptable et restitution du trop-perçu ; corriger les compteurs/quota concernés |
| Génération techniquement échouée ou document illisible | Correction/régénération sans surcoût ; restitution du crédit ou remboursement du supplément facturé si la prestation supplémentaire ne peut être fournie |
| Rapport contenant une erreur factuelle/IA | Examiner, corriger avant signature ou par complément traçable ; ne pas écraser l'acte signé ; examiner les recours selon gravité et contrat |
| Indisponibilité du service | Avoirs selon SLA si celui-ci a été accepté ; les autres recours ne sont pas exclus |
| Résiliation justifiée par manquement de Tenu | Pas de mensualités futures d'engagement ; remboursement des sommes prépayées relatives à la période non fournie selon le contrat |
| Issue défavorable d'un litige locatif | Pas de remboursement fondé sur ce seul résultat ; les éventuels défauts propres du service restent examinés |

Ces paramètres sont proposés pour acceptation juridique/commerciale. Les avoirs SLA, restitutions de trop-perçu et remboursements ne doivent pas indemniser deux fois le même montant ; la règle ne limite pas les droits à réparation distincts.

### 3.3 Demandes et paiements

Canal principal : support@tenu.world, avec agence, référence de contrat/facture/dossier et motif. Ne pas rejeter une demande valable reçue autrement ; la réorienter et conserver sa date de réception.

Objectifs proposés : accusé de réception sous deux jours ouvrés et réponse de fond sous dix jours ouvrés ; si une enquête exige plus de temps, informer l'agence du motif et du calendrier. Une fois le remboursement accepté, ordre de remboursement sous quatorze jours calendaires, ou délai impératif plus favorable applicable. Le délai d'inscription bancaire dépend du prestataire et de la banque ; aucune garantie non vérifiée de délai Stripe n'est donnée.

Rembourser sur le moyen de paiement initial sauf impossibilité documentée ou autre accord licite ; aucun avoir imposé à la place d'une restitution due. Un avoir commercial volontaire et un avoir comptable rectificatif sont distingués.

Une contestation bancaire n'entraîne pas automatiquement une suppression du compte ou des preuves. Toute suspension repose sur les conditions d'abonnement, une analyse et des mesures proportionnées, avec préservation de la remise/export compatibles avec la sécurité.

## 4. Corrections des anciens textes avant publication

- Distinguer SaaS professionnel, contenus à l'acte et contrats B2C historiques.
- Adapter les bases légales, rôles et durées à chaque finalité ; ne pas déduire la conformité du simple changement de vocabulaire.
- Vérifier la référence de rétractation : l'article L221-28 distingue les services et les contenus numériques, au 1° et au 13°. L'ancien renvoi au 1° pour un contenu numérique ne doit pas être repris sans qualification exacte.
- Supprimer l'ancien lien ODR, revoir la clause de tribunal et supprimer toute promesse de résultat locatif.
- Réconcilier les trois politiques entre elles et avec le bon de commande, le parcours de paiement, l'article 28 et les notices aux invités.
- La présente rédaction dans le dépôt ne modifie ni les pages applicatives ni le site déployé.

Références officielles : [article L221-28](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000044563170/), [DGCCRF — petits professionnels hors établissement](https://www.economie.gouv.fr/dgccrf/les-fiches-pratiques/petits-professionnels-vous-avez-14-jours-pour-vous-retracter-en-cas-de-contrat-conclu-hors-etablissement), [CNIL — droits](https://www.cnil.fr/fr/mes-demarches/les-droits-pour-maitriser-vos-donnees-personnelles).

## 5. Documents liés et validation

[Conditions B2B](03-Projet-Conditions-Abonnement-B2B.md) — [Annexe RGPD](04-Projet-Annexe-RGPD-Securite.md) — [Paramètres techniques/assurance](06-Parametres-Conservation-Signature-Service-Assurance.md).

Avant publication : valider les délais de remboursement et les proratas, confirmer TVA/immatriculation, prestataires et contrats effectifs, finaliser l'information des participants et documenter la décision de publication. Aucun fournisseur n'est contacté et aucune page publique n'est déployée dans cette étape.
