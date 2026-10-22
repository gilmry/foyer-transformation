# Étape 3 : Adhésion

## But

Passer de « il faudrait » à « je veux essayer », en montrant des mécanismes qui répondent aux risques nommés à l'étape 2.

## Entrée

- Le registre des risques de l'étape 2.
- Un scénario de démonstration sur un environnement de démonstration, jamais sur la production de l'organisation.

## Sortie vérifiable

- Un compte rendu de la démonstration : ce qui a été montré, ce qui a marché, ce qui n'a pas marché.
- Une personne nommée qui accepte de porter le changement, avec du temps réservé à son agenda.
- Un premier périmètre choisi par l'organisation pour l'étape 5 : une application réelle, de taille modeste.

## Le scénario de démonstration

Deux mécanismes, choisis parce qu'ils répondent aux deux risques qui reviennent le plus souvent : perdre ses données et laisser passer une mise en production non vérifiée.

1. **La restauration nocturne.** Une seconde production éphémère est reconstruite depuis la sauvegarde hors site, vérifiée, puis détruite. Le lendemain, on lit la durée mesurée et le résultat. Une sauvegarde déclarée réussie ne prouve rien ; sa restauration, si.
2. **La chaîne d'approbation.** Un agent prépare une mise en ligne, la demande, et s'arrête. Une personne nommée lit le plan et approuve ou refuse. L'agent ne détient pas les droits de mettre en production : il ne peut que demander.

Si l'un de ces mécanismes n'est pas encore en service, on le dit et on montre ce qui existe, par exemple une restauration manuelle chronométrée.

## Déclinaison développeurs

La démonstration se fait dans le terminal et dans la CI : une gate rouge qui bloque, une demande de mise en ligne en attente, le journal de restauration. Les développeurs posent leurs objections techniques, qui sont notées et reçoivent une réponse écrite.

## Déclinaison dirigeants

La démonstration se fait à partir des preuves : le rapport de restauration du matin, l'enregistrement de l'approbation avec le nom de la personne et l'heure. Le dirigeant voit ce qu'il pourra montrer à un auditeur, un client ou un juge, et ce qu'il ne pourra pas montrer tant que le mécanisme n'existe pas chez lui.

## Lien avec Foyer et Sluis

- La chaîne d'approbation est celle de Sluis : niveau Tier 1, environnement GitHub protégé à relecteurs requis.
- La restauration nocturne d'une seconde production éphémère est proposée dans Sluis (ADR-020, statut proposé). Elle n'est pas encore en service à la date de ce document.
- Le principe Foyer « l'outil objective, l'humain décide » est ce que la démonstration rend visible.

## Ce qui relève du dépôt privé

- Le script de démonstration pas à pas et l'environnement de démonstration.
- Les réponses types aux objections fréquentes.
- Les comptes rendus de démonstration chez les organisations accompagnées.
