# Tenu — Spécification active du parcours propriétaire

29 octobre 2026. Produit prévu ; les fonctions ci-dessous ne sont pas attestées comme implémentées.

## Utilisateurs et rôles

Propriétaire particulier acheteur/administrateur de ses logements ; candidat locataire déposant ; garant si nécessaire ; locataire participant au bail/EDL ; mandataire habilité. Cloisonner les accès par dossier, rôle et étape ; un candidat ne voit pas les autres. Pas d'achat candidat obligatoire.

France, locations vides/meublées de résidence principale. Les baux particuliers hors périmètre sont bloqués par le générateur jusqu'à validation. Langues offertes à définir avec relecture des textes.

## Modules

| Module | Entrées / sorties | Contrôle requis |
|---|---|---|
| Onboarding logement | Régime, propriétaire/pouvoirs, adresse, données et contraintes | Qualification du client/du bail ; pas d'inférence du régime selon nationalité |
| Candidatures | Pièces autorisées, équivalents étrangers, dépôt sécurisé | Notice, minimisation, destinataires, délai et droits |
| Contrôle documentaire | OCR et contrôles localisés, anomalies/non vérifiable/source vérifiée | Ne pas certifier l'authenticité ; source, date, portée et erreurs |
| Rating personnel | Pièces et facteurs validés, note/explication ou non évalué | Profilage/AI Act, méthode, test de biais, décision humaine et réexamen |
| Bail | Template vide/meublé, clauses/règles locales/annexes | Données vérifiées, aucune invention libre, versions et relecture |
| Guidage entrée/sortie | Pièces/éléments, photo/vidéo, clés/compteurs, réserves | Étape manquante visible, capture proportionnée, audio proposé désactivé |
| Comparaison | État préexistant, usure/vétusté, dommage possible/indéterminé | Grille convenue, preuve, limites, validation et coût distinct |
| Traductions | Notices/résultats/rapports/bail explicatifs | Langue supportée, référence/version et revue humaine |
| Signature/remise | Accord réel des parties, annexes, preuve et exemplaires | Pas de statut signé artificiel ni de lien temporaire comme seule preuve |
| Conservation/export | Médias, documents, candidature et logs classés | Calendriers distincts, gels ciblés, sauvegardes et copies dérivées |

## Rating : définition produit obligatoire

Finalité exacte, variables/pondérations, échelle, seuils d'usage, validité, supports documentaires et explications restent à fixer. Ce n'est ni une note publique, ni une réputation inter-bailleurs, ni un système de décision automatique. Documents incomplets/étrangers peuvent entraîner « non évalué », jamais fraude ou rejet par défaut. Le score de candidature n'est pas utilisé pour imputer un dégât à la sortie.

## Bail et états des lieux

Deux objets distincts du contrat Tenu/propriétaire. Bail français de référence à partir des contrats types ; traductions explicatives. Un EDL préparé par une seule personne reste unilatéral tant que le processus contradictoire/accord/signature n'est pas réalisé. Conserver réserves et compléments.

Les vidéos sont des fichiers à remettre/exporter avec inventaire/empreinte, pas une vidéo éternellement embarquée dans un PDF. Images fixes intégrées au signé et vidéo source ont des cycles différents.

## Données et commande

Aucun entraînement sur médias, pièces, scores ou dérivés. Stockage UE chiffré à démontrer par catégorie ; résidence du stockage distincte de l'inférence. Photos/vidéos séparées : douze mois après sortie effective. Candidatures non retenues, scores et baux : règles distinctes, pas de purge uniforme.

Achat à l'acte/dossier ; prix TTC, modules inclus, quotas/délais, correction, rétractation et garanties avant paiement. Aucun abonnement agence ni option précochée. Les objectifs de service anciens sont à revalider pour ce parcours.

## Critères de recette

Documents étrangers et formats non reconnus ; pièces interdites ; contresens multilingue ; rating contesté/corrigé ; prompt injection ; dossier mal attribué ; bail vide/meublé avec paramètres locaux manquants ; absence/refus de signature ; annexe vidéo inaccessible ; purge et restauration ; âge d'équipement inconnu et grille absente.

Références : [Legal 11](../05-Legal-Compliance/11-Cadre-Proprietaires-Parcours-Location.md), [12](../05-Legal-Compliance/12-Analyse-Dossiers-Rating-IA.md), [13](../05-Legal-Compliance/13-Template-Bail-Vide-Meuble.md), [14](../05-Legal-Compliance/14-Notices-Locataires-Multilingues.md).
