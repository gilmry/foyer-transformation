# Étape 4 : Formation

## But

Donner à chaque personne les gestes de son rôle, en cohortes par rôle plutôt qu'en formation générale.

## Les trois rôles

| Rôle | Ce que la personne fait | Ce qu'elle doit savoir lire |
|---|---|---|
| **Écrire** | produit le code, les tests, les décisions (ADR), seule ou avec un agent | un test qui échoue, une gate rouge, un écart de contrat |
| **Approuver** | autorise une mise en ligne ou un choix irréversible, et en répond | un diff, un plan d'infrastructure, un rapport de gates |
| **Opérer** | fait tourner, surveille, restaure | une alerte, un journal, un rapport de restauration |

Une même personne peut tenir plusieurs rôles, mais jamais écrire et approuver le même changement.

## Entrée

- Le périmètre choisi à l'étape 3.
- La liste des personnes par rôle, avec au moins deux personnes par rôle pour éviter la dépendance à une seule.

## Sortie vérifiable

- Pour chaque personne formée, un geste réel exécuté et enregistré : un changement passé par les gates (écrire), une approbation motivée (approuver), une restauration exécutée documentation en main (opérer).
- Au moins deux personnes capables de tenir chaque rôle sur le périmètre visé.

## Déclinaison développeurs

Cohortes **écrire** et **opérer** surtout. Contenu : la boucle de craft de Foyer (test d'abord, ordre des couches, gates en local avant de pousser), le travail avec un agent qui produit et rend son raisonnement visible, la lecture d'un rapport de restauration. On travaille en binôme ou en trio, conformément à Foyer.

## Déclinaison dirigeants

Cohorte **approuver** surtout. Contenu : lire une décision d'architecture et ses alternatives écartées, reconnaître un choix irréversible, poser la question de modalité plutôt que trancher la destination, savoir refuser une approbation qu'on ne comprend pas. Objectif : que l'approbation reste une décision, pas une signature.

## Lien avec Foyer et Sluis

- Le rôle **écrire** suit la boucle de craft et le pilote Foyer (`Methode-Foyer.md` §2, `pilote/`).
- Le rôle **approuver** correspond aux relecteurs requis de l'environnement protégé dans Sluis, et à l'arbitrage du pilote Foyer (`pilote/arbitrage.md`).
- Le rôle **opérer** s'appuie sur les rapports de Sluis.

## Ce qui relève du dépôt privé

- Les supports de formation détaillés de chaque cohorte.
- Les exercices et leurs corrigés.
- Les feuilles de présence et les évaluations des cohortes.
