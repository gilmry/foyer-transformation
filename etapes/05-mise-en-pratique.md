# Étape 5 : Mise en pratique

## But

Appliquer la méthode à un vrai produit, avec de vrais utilisateurs, sous accompagnement, et éprouver la reprise au moins une fois.

## Entrée

- Le périmètre choisi à l'étape 3.
- Les personnes formées à l'étape 4, au moins deux par rôle.
- L'accord écrit de la personne qui répond du produit pour mener le pilote.

## Sortie vérifiable

- Au moins une mise en ligne réelle passée par toute la chaîne : gates vertes, demande, approbation par une personne nommée, mise en ligne, rapport.
- Le compte rendu d'un **premier exercice de reprise** : scénario, heure de début, heure de reprise, durée mesurée, écarts constatés, actions décidées.
- La liste des arbitrages irréversibles rencontrés pendant le pilote, chacun avec le nom de la personne qui l'a tranché.

## L'exercice de reprise

On simule une perte (base de données, serveur, accès) sur un environnement prévu pour cela, jamais sur la production. L'équipe reprend le service avec la documentation existante. L'accompagnant observe et n'intervient pas, sauf risque réel. Ce qu'on mesure : la durée, ce qui manquait, qui savait faire. Un exercice qui échoue est un résultat utile, à condition d'être écrit.

## Déclinaison développeurs

Le pilote se mène avec le pilote Foyer : le registre d'état du projet tenu à jour, un commit par étape conclusive, une gate rouge qui arrête tout. L'exercice de reprise est exécuté par les personnes du rôle **opérer**, pas par l'accompagnant.

## Déclinaison dirigeants

La direction tient son rôle d'approbation sur de vraies demandes et tranche les arbitrages qu'on lui présente. Elle assiste à l'exercice de reprise ou en lit le compte rendu le jour même, et décide des actions qui en découlent.

## Lien avec Foyer et Sluis

- Le pilote suit un parcours du pilote Foyer : rétrofit pour une application existante, nouveau projet sinon.
- La mise en ligne passe par la chaîne d'approbation de Sluis.
- Les exercices de reprise trimestriels sont proposés dans Sluis (ADR-036, statut proposé). Le premier exercice de l'étape 5 en est la première occurrence.

## Ce qui relève du dépôt privé

- Le guide d'accompagnement du pilote.
- Les scénarios d'exercice de reprise.
- Les comptes rendus de pilote et d'exercice des organisations accompagnées.
