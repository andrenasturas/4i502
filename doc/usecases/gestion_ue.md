## UC Gérer les UE

* Créé le 06/10/16
* Mis à jour le 06/10/16
* Écrite par Damien Serin
* Version 1.0

### Description

La gestion des UE permet à l'Enseignant d'ajouter, éditer et supprimer des UE.

### Acteurs concernés

* Enseignant

### Pré-Conditions

* Aucune

### Scénario nominal

1. L'Enseignant demande l'affichage de la liste des UE.
2. Le Système affiche la liste des UE.
3. L'Enseignant choisit d'éditer une UE existante.
4. Le Système vérifie si l'enseignant est bien le créateur de cette UE.
5. Le Système affiche la page d'édition de l'UE.
6. L'Enseignant modifie les champs souhaités.
7. L'Enseignant valide sa modification.
8. Le Sytème notifie l'Enseignant de la modification.

### Post-Conditions

* Les modifications sont appliquées.

### Alternatives possibles

1. L'Enseignant n'est pas le créateur de l'UE	.
    1. Cette alternative se déclenche après l'étape 4 du scénario nominal.
    2. Le Système affiche un message d'erreur sur l'application web.
    3. Le scénario nominal reprend à l'étape 2.

2. L'Enseignant souhaite créer une UE.
    1. Cette alternative se déclenche après l'étape 2 du scénario nominal.
    2. L'Enseignant choisit de créer une nouvelle UE.
    3. Le Sytème notifie l'Enseignant de la création d'une nouvelle UE. 
    4. Le scénario nominal reprend à l'étape 2.

3. L'Enseignant souhaite supprimer une UE.
    1. Cette alternative se déclenche après l'étape 4 du scénario nominal.
    2. L'Enseignant choisit de supprimer l'UE selectionnée.
    3. Le Système demande une confirmation de la suppression.
    4. L'Enseignant confirme la demande de suppression.
    5. Le Système notifie l'Enseignant de la suppression de l'UE.
    6. Le scénario nominal reprend à l'étape 2.

### Exceptions possibles

2. L'Enseignant souhaite annuler son action.
    1.  Cette alternative se déclenche après les étapes 2, 5 ou 6 du scénario nominal.
// DAMIEN FAIS LE PLEASE KEUR KEUR SUR TOI
