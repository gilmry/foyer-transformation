# Questionnaire de diagnostic

Vingt questions, regroupées par étape, pour situer la première étape où l'organisation bloque. Comptez trente minutes.

## Comment répondre

- **Deux répondants au moins**, qui répondent séparément : une personne de la direction, une personne qui livre du logiciel. Les écarts entre leurs réponses sont un résultat en soi.
- Pour chaque question, une note :
  - **0** : non, ou je ne sais pas ;
  - **1** : en partie, ou seulement à l'oral ;
  - **2** : oui, et je peux montrer la preuve (un lien, un document, une date).
- Pas de preuve, pas de 2. Une pratique réelle mais jamais écrite vaut 1.

## Les questions

### Étape 1 : Diagnostic (savoir où l'on en est)

| # | Question | Note |
|---|---|---|
| 1 | Il existe une liste à jour des applications de l'organisation, avec pour chacune la personne qui en répond. | |
| 2 | Pour chaque application critique, on sait où se trouvent ses données et ses sauvegardes. | |
| 3 | Les décisions techniques importantes des douze derniers mois sont écrites, avec leur motif et les alternatives écartées. | |

### Étape 2 : Prise de conscience (savoir pourquoi changer)

| # | Question | Note |
|---|---|---|
| 4 | La direction peut citer les trois risques numériques qui arrêteraient l'organisation le plus longtemps. | |
| 5 | Le dernier incident ou presque-incident a été analysé par écrit, sans chercher de coupable. | |
| 6 | Les personnes qui livrent savent ce que coûterait une journée d'arrêt de l'application principale. | |
| 7 | Les systèmes qui dépendent d'une seule personne sont identifiés. | |

### Étape 3 : Adhésion (vouloir essayer)

| # | Question | Note |
|---|---|---|
| 8 | Au cours des six derniers mois, la direction ou l'équipe a vu une restauration complète réussir depuis une sauvegarde. | |
| 9 | Une personne nommée porte le changement et y consacre du temps réservé à son agenda. | |
| 10 | L'organisation a choisi elle-même un premier périmètre réel où essayer la méthode. | |

### Étape 4 : Formation (savoir faire)

| # | Question | Note |
|---|---|---|
| 11 | Chaque rôle (écrire, approuver, opérer) peut être tenu par au moins deux personnes sur le périmètre visé. | |
| 12 | Les personnes qui approuvent une mise en ligne savent lire ce qu'elles approuvent : diff, plan, rapport de tests. | |
| 13 | Les personnes qui opèrent ont déjà exécuté elles-mêmes une restauration, documentation en main. | |
| 14 | Les développeurs lancent les contrôles automatiques (tests, analyse, sécurité) avant d'envoyer leur code, et pas seulement en CI. | |

### Étape 5 : Mise en pratique (le faire pour de vrai)

| # | Question | Note |
|---|---|---|
| 15 | Un produit réel, avec de vrais utilisateurs, est mis en ligne uniquement après approbation enregistrée d'une personne nommée. | |
| 16 | Un exercice de reprise a eu lieu, avec durée mesurée et écarts écrits. | |
| 17 | Les choix irréversibles récents ont été tranchés par une personne nommée, et c'est écrit. | |

### Étape 6 : Ancrage (que ça tienne)

| # | Question | Note |
|---|---|---|
| 18 | Chaque mise en ligne produit un rapport de preuves conservé (contrôles passés, approbation, version). | |
| 19 | Une revue à date fixe, au moins trimestrielle, relit ces preuves et ses décisions sont suivies d'une revue à l'autre. | |
| 20 | Le dispositif a continué de fonctionner pendant l'absence de la personne qui l'a mis en place. | |

## Grille de lecture

1. Pour chaque étape, regardez les notes du répondant.
2. Une étape est **acquise** si elle n'a **aucun 0** et si **au moins la moitié** de ses questions ont 2.
3. L'étape de blocage est la **première étape non acquise**, dans l'ordre de 1 à 6. C'est par elle que l'accompagnement commence.
4. Si une étape est acquise alors qu'une étape antérieure ne l'est pas, on commence quand même par l'étape antérieure : ce qui est construit au-dessus tient mal.
5. Si les répondants n'arrivent pas à la même étape de blocage, on retient **la plus basse**, et l'écart devient un sujet de l'atelier de prise de conscience.
6. Si les six étapes sont acquises, le kit n'a rien à apporter. Rejouez le questionnaire à chaque revue trimestrielle pour vérifier qu'aucune étape ne recule.

### Exemple

| Étape | Notes | Acquise ? |
|---|---|---|
| 1 | 2, 2, 1 | oui |
| 2 | 2, 1, 2, 2 | oui |
| 3 | 0, 2, 1 | non (un 0) |
| 4 | 2, 1, 1, 2 | oui |
| 5 | 1, 0, 1 | non |
| 6 | 0, 0, 1 | non |

Étape de blocage : **3, Adhésion**. L'étape 4 semble acquise, mais on ne s'y appuie pas tant que l'étape 3 ne tient pas.

## Limites

Ce questionnaire est une base, pas un audit. Il ne mesure ni la qualité du code ni la conformité à une norme. Il dit seulement par où commencer.
