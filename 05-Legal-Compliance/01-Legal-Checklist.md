# Tenu — Checklist juridique et conformité B2B France

Version 2.0 — 28 octobre 2026  
Responsable de revue : responsable juridique. Statut : exigences à vérifier, aucune case n'atteste une réalisation.


## Précisions du responsable juridique — 29 octobre 2026

**Stockage :** les photos sont stockées chiffrées chez Cloudflare dans l'Union européenne, selon les informations communiquées par le responsable juridique. Cette précision est intégrée au cadre documentaire ; la configuration, l'entité Cloudflare contractante, la région effective, la gestion des clés, les accès de support et les garanties de transfert restent à documenter dans la cartographie technique. Le chiffrement du stockage ne doit pas être présenté comme du chiffrement de bout en bout sans dispositif correspondant.

**Interdiction d'entraînement :** les photos et leurs copies ne sont jamais utilisées pour entraîner ou affiner des modèles d'intelligence artificielle, par Tenu ou par ses prestataires. Cette interdiction est contractuelle et doit être répercutée dans le choix, les conditions et les réglages des API IA. Leur analyse pour générer les constats relève de l'inférence, avec rétention temporaire limitée ; elle n'autorise aucun entraînement. Aucune dérogation d'entraînement n'est prévue par cette offre.

**Purge à douze mois :** les fichiers photo séparés d'entrée et de sortie sont supprimés de la production douze mois après la date effective de sortie du locataire, renseignée et vérifiée par l'agence. Le délai ne court ni depuis le téléversement ni depuis la signature du constat d'entrée. Les photos intégrées aux PDF signés ne sont pas concernées par cette purge : les PDF et leurs éléments de preuve suivent leur calendrier documentaire propre, sans retrait ni altération des images. Les fichiers inutilisés et copies temporaires peuvent être supprimés plus tôt selon les délais dédiés. Les sauvegardes expirent selon leur cycle documenté, sans réactivation après restauration ; un gel contentieux ciblé ou une obligation légale peut suspendre une purge, avec motif, accès restreint et revue périodique. L'information des personnes doit distinguer explicitement suppression des fichiers séparés et maintien des images dans les PDF. La fin du service reste régie par la restitution/suppression, et n'impose pas une conservation par Tenu jusqu'à cette échéance.

**Grille de vétusté :** référence retenue : [article 4 du décret n° 2016-382 du 30 mars 2016](https://www.legifrance.gouv.fr/loda/article_lc/LEGIARTI000032324427). Le décret encadre la prise en compte de la vétusté et le choix d'une grille issue d'un accord collectif ; il ne fournit pas une grille nationale chiffrée unique. Renseigner dans chaque dossier la grille retenue, sa version, l'accord collectif source et son acceptation par les parties au bail. Une grille interne non justifiée ne doit pas être présentée comme réglementaire. L'IA ne choisit pas seule la grille et ne décide pas de l'imputabilité ou d'une retenue.

## Périmètre adopté

Agences immobilières en France, notamment au service d'expatriés ; états des lieux signés assistés par IA. Pilote de 30 jours sans poursuite automatique ; engagement payant initial de 12 mois facturé mensuellement ; poursuite mensuelle résiliable avec préavis de 30 jours.

Documents : [cadre](02-Cadre-B2B-Agences-France.md), [conditions proposées](03-Projet-Conditions-Abonnement-B2B.md), [annexe RGPD/sécurité](04-Projet-Annexe-RGPD-Securite.md), [risques](../07-Risk/01-Risk-Register.md).

## Compléments à clôturer

- [ ] Technique/données : documenter le stockage photo Cloudflare UE chiffré, ses accès et clés.
- [ ] Technique/juridique : vérifier les clauses et paramètres interdisant tout entraînement sur les photos chez chaque prestataire.
- [ ] Technique/produit : tester la purge des photos séparées douze mois après sortie effective, la conservation des photos intégrées aux PDF signés et la gestion des sauvegardes/gels ; informer les personnes de cette distinction.
- [ ] Juridique : valider la grille issue d'un accord collectif, sa version et l'accord des parties conformément à l'article 4 du décret du 30 mars 2016.

## Avant tout pilote avec dossiers réels

- [ ] Juridique : confirmer entité contractante, pouvoirs, périmètres de baux et mandat de l'agence.
- [ ] Juridique/produit : vérifier toutes les mentions du décret du 30 mars 2016 et la comparaison entrée/sortie.
- [ ] Produit : garantir lecture, corrections, réserves et validation contradictoire avant signature.
- [ ] Technique/juridique : choisir le dispositif de signature, vérifier identification, consentement, intégrité et dossier de preuve.
- [ ] Technique : tester remise à chaque partie au moment de la signature, erreurs et solution alternative.
- [ ] Produit : traiter refus/absence de signature sans fabriquer un accord.
- [ ] Produit : gérer les demandes de complément d'entrée sous dix jours et le chauffage pendant le premier mois de chauffe ; conserver les versions.
- [ ] Juridique : vérifier le régime des meublés/inventaires et exclure les régimes non validés.
- [ ] Protection des données : qualifier les rôles réels, bases légales, information et nécessité d'une analyse d'impact.
- [ ] Juridique : finaliser et signer l'annexe article 28, y compris pendant le pilote.
- [ ] Technique : cartographier les prestataires réels, régions, accès hors EEE et garanties de transfert.
- [ ] Technique : tester séparation entre agences, comptes et révocation, stockage privé, liens, sauvegardes et restauration.
- [ ] Juridique/technique : fixer conservation, gel pour contentieux, export et suppression jusque chez les prestataires.
- [ ] Technique : vérifier contractuellement rétention et absence d'entraînement chez les prestataires IA.
- [ ] Produit : vérifier les constats IA, omissions, traductions et validations humaines sur des dossiers représentatifs.
- [ ] Juridique/produit : documenter la qualification AI Act et les obligations applicables à la destination réelle.
- [ ] Direction : confirmer assurance adaptée au SaaS, à l'IA et aux preuves locatives.

### Contrôles spécifiques au template et aux photos

- [ ] Produit/juridique : valider le [template commun](05-Template-Etat-des-Lieux-Photos.md), ses versions et les mentions obligatoires.
- [ ] Produit : rattacher chaque photo à la phase, pièce et élément ; comparer entrée/sortie sans altérer le document d'entrée.
- [ ] Technique : intégrer les photos retenues au PDF ou aux annexes figées liées à la signature ; vérifier relecture et remise des images aux parties sans dépendre de liens expirants.
- [ ] Données/juridique : valider les délais proposés section 6 de l'annexe RGPD et les communiquer avant collecte.
- [ ] Technique : tester la purge des non-retenues, brouillons, caches, versions d'objets et copies prestataires, ainsi que les appareils gérés.
- [ ] Technique/juridique : tester qu'un gel contentieux bloque uniquement les purges concernées ; ne pas supprimer une photo probatoire d'entrée avant comparaison de sortie.
- [ ] Technique : tester la non-réapparition après restauration et tracer les purges/échecs sans conserver une copie des images.
- [ ] Juridique : préciser le sort des photos incluses dans les PDF signés et les limites de suppression des exemplaires remis/exportés.

## Avant abonnement payant

- [ ] Commercial : fixer tarifs HT/TVA, utilisateurs, volumes, reports, dépassements et coût des signatures.
- [ ] Juridique : compléter tous les champs ouverts des conditions et du bon de commande.
- [ ] Produit : recueillir l'acceptation explicite du payant et archiver les versions contractuelles.
- [ ] Facturation : distinguer dates du pilote, activation payante, terme initial et échéances mensuelles.
- [ ] Produit : tester non-poursuite, préavis de 30 jours, absence de réengagement annuel et accusé de réception.
- [ ] Juridique : finaliser retard de paiement, responsabilité, assurance et sorties anticipées.
- [ ] Technique/direction : valider les engagements d'assistance, disponibilité et réversibilité avant de les promettre.
- [ ] Juridique/fiscalité : vérifier TVA et facturation selon l'entité et la situation effectives ; ne pas réutiliser le seuil de l'ancien document.
- [ ] Marketing : supprimer les promesses d'objectivité absolue, d'absence de litige ou de résultat garanti.
- [ ] Équipe : réaligner stratégie, produit, finances, marketing et parcours applicatifs encore fondés sur le B2C/UK.

## Finalisation des quatre volets

Les [paramètres proposés pour les quatre volets](06-Parametres-Conservation-Signature-Service-Assurance.md) proposent les modalités à finaliser.
- [ ] Juridique/agence : qualifier la mission de gestion, fixer la durée et le point de départ d'archivage après clôture des comptes, valider les délais des autres catégories.
- [ ] Produit/technique : sélectionner le prestataire de signature (À confirmer), vérifier le niveau de l'offre exacte et réaliser la recette du parcours complet.
- [ ] Technique/direction : accepter ou ajuster les objectifs 99,5 %, support ouvré, RPO/RTO, mesure, maintenance et recours ; démontrer les capacités avant contrat.
- [ ] Direction/courtier : confirmer assureur/police, déclaration SaaS/IA/signature et données, couverture du pilote et garanties/plafonds/franchises.
- [ ] Juridique : finaliser le plafond de responsabilité et les clauses d'assurance après réponses du courtier.
- [ ] Juridique : identifier nominativement les validateurs et consigner décisions, date et preuves ; aucune case n'est close par la seule rédaction.

## Contrôles récurrents

| Contrôle | Fréquence proposée | Responsable |
|---|---|---|
| Accès, incidents, remises et signatures en échec | Suivi opérationnel continu | Technique |
| Risques et actions | Mensuelle | Juridique + direction |
| Qualité des constats/traductions après changement IA | Avant déploiement | Produit |
| Habilitations et prestataires | Trimestrielle et à chaque changement | Technique / données |
| Veille juridique et conditions | Trimestrielle, puis à changement significatif | Juridique |
| Restauration et export | Trimestrielle | Technique |
| Conservation et purges | Selon calendrier validé, revue annuelle | Données / juridique |

## Corrections de l'ancien cadre

La vente B2C, le Royaume-Uni, la commission de récupération et les courriers contentieux autonomes sortent de cette offre. Le consentement générique, la purge universelle des photos à 30 jours, l'exonération totale de responsabilité, la qualification automatique de toute photo comme donnée sensible et les anciennes hypothèses fiscales/techniques ne sont pas repris.

Sources et fondements : voir le cadre B2B. La rédaction de ces documents ne signifie pas que les contrôles sont implémentés.
