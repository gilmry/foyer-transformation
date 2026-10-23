# Étape 1 : Diagnostic

## But

Situer où l'organisation bloque, pour commencer au bon endroit plutôt que de dérouler tout le parcours par défaut.

## Entrée

- Une personne de la direction et au moins une personne qui livre du logiciel, disponibles pour répondre séparément.
- Le [questionnaire de diagnostic](../diagnostic/questionnaire.md).

## Sortie vérifiable

- Les questionnaires remplis, un par répondant, avec pour chaque réponse « oui » la preuve qui la justifie (un lien, un document, une date).
- L'étape de blocage identifiée selon la grille de lecture.
- La liste des écarts entre les réponses de la direction et celles des équipes. Un écart est une information, pas une faute.

## Déclinaison développeurs

Les questions portent sur ce que l'équipe fait réellement : les tests précèdent-ils le code, les gates tournent-elles avant de pousser, une restauration a-t-elle déjà été exécutée, qui peut mettre en ligne. On répond depuis le dépôt et la CI, pas de mémoire.

## Déclinaison dirigeants

Les questions portent sur ce que la direction sait et décide : la liste des applications et de qui en répond, les décisions techniques écrites, les risques connus. On répond depuis les documents existants. Si la preuve n'existe pas, la réponse est « non », même quand la pratique existe à l'oral.

## Lien avec Foyer et Sluis

- Le diagnostic reprend la logique du parcours **rétrofit** du pilote Foyer (`pilote/journeys/retrofit.md`) : constater avant d'agir.
- Il applique la règle de Foyer selon laquelle une valeur se mesure, elle ne se recopie pas.
- Il ne demande pas Sluis : on constate l'existant, quel qu'il soit.

## Ce qui relève du dépôt privé

- La version animée du questionnaire (guide d'entretien, relances).
- Le gabarit de restitution remis à l'organisation.
- Les questionnaires remplis par les organisations accompagnées.
