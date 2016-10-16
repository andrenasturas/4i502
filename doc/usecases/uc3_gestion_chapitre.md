## UC3 Gestion des chapitres

* Créé le 13/10/16
* Mis à jour le 16/10/16
* Écrite par Sandra Laduranti
* Version 1.0.1

### Description

La Gestion des chapitres permet à l'Enseignant d'ajouter, éditer et supprimer des chapitres liés à une UE.

### Acteurs concernés

* Enseignant

### Pré-Conditions

* L'UE concernant le chapitre à éditer existe.
* L'Enseignant est le créateur de l'UE où le chapitre est lié.

### Scénario nominal

1. L'Enseignant selectionne l'UE concernant le chapitre à éditer.
2. Le Système affiche la liste des chapitres.
3. L'Enseignant choisit d'éditer un chapitre existant.
4. Le Système affiche la page d'édition du chapitre.
5. L'Enseignant modifie les champs souhaités.
6. L'Enseignant valide sa modification.
7. Le Système notifie l'Enseignant de la modification.

### Post-Conditions

* Les modifications sont appliquées.

### Alternatives possibles

1. L'Enseignant souhaite ajouter un chapitre.
    1. Cette alternative se déclenche après l'étape 2 du scénario nominal.
    2. L'Enseignant choisit de créer un nouveau chapitre.
    3. Le Système notifie l'Enseignant de la création du nouveau chapitre.
    4. Le scénario nominal reprend à l'étape 2.

2. L'Enseignant souhaite supprimer un chapitre.
    1. Cette alternative se déclenche après l'étape 4 du scénario nominal.
    2. L'Enseignant choisit de supprimer le chapitre selectionné.
    3. Le Système demande une confirmation de la suppression.
    4. L'Enseignant confirme la demande de suppression.
    5. Le Système notifie l'Enseignant de la suppression du chapitre.
    6. Le scénario nominal reprend à l'étape 2.

### Exceptions possibles

2. L'Enseignant souhaite annuler son action.
    1. Cette alternative se déclenche après les étapes 2, 5 ou 6 du scénario nominal.
    2. L'Enseignant sélectionne "Annuler l'opération".
    3. Le Système affiche la page de l'UE.
