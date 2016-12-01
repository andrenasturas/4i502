## UC5 Gestion des questions
* Créé le 06/10/16
* Mis à jour le 16/10/16
* Écrite par Sandra Laduranti
* Version 1.2.0

### Description

La gestion des questions permet à l'Enseignant d'ajouter, éditer et suppprimer des questions.

### Acteur(s) concerné(s)

* Enseignant

### Pré-Conditions

* Aucune

### Scénario nominal

1. L'Enseignant demande l'affichage de la liste des UE.
2. Le Système affiche la liste des UE.
3. L'Enseignant choisit l'UE et le Chapitre pour lequel il souhaite consulter la liste des questions.
4. L'Enseignant sélectionne une question existante à modifier.
5. Le Système affiche la page d'édition d'une question.
6. L'Enseignant modifie les champs souhaités.
7. L'Enseignant valide les modifications.
8. Le Système notifie l'Enseignant de la modification.

### Post-Conditions

* Le Système a enregistré l'action de l'Enseignant.

### Alternatives possibles

A1. L'Enseignant souhaite ajouter une nouvelle question.
    1. Cette alternative se déclenche après l'étape 3 du scénario nominal.
    2. Le Sytème affiche le formulaire d'ajout d'une question.
    3. L'Enseignant renseigne les champs du formulaire d'ajout d'une question.
    4. L'Enseignant valide l'ajout d'une question.
    5. Le Système notifie l'ajout d'une question au chapitre souhaité.
    6. Le scénario nominal reprend à l'étape 2.

A2. L'Enseignant n'est pas le propriétaire de l'UE.
    1. Cette alternative se déclenche après l'étape 3 du scénario nominal.
    2. Le Système affiche un message d'erreur sur l'application web.
    3. Le scénario nominal reprend à l'étape 2.

A3. L'Enseignant souhaite supprimer la question sélectionnée.
    1. Cette alternative se déclenche après l'étape 5 du scénario nominal.
    2. L'Enseignant clique sur le bouton permettant de supprimer la question sélectionnée.
    3. Le Système demande à l'enseignant de confirmer la suppression de la question.
    4. L'Enseignant confirme la demande de suppression.
    5. Le Système notifie l'enseignant de la suppression de la question.
    6. Le scénario nominal reprend à l'étape 2.

### Exceptions possibles

E1. L'Enseignant annule l'action en cours.
    1. Cette exception se déclenche après l'étape 3, 6 ou 7 du scénario nominal, ou après l'étape 2 ou 3 du scénario alternatif A1, ou après l'étape 3 du scénario alternatif A3.
    2. L'Enseignant clique sur le bouton d'annulation.
    3. Le Système notifie l'enseignant de l'annulation de l'action en cours.
    4. Le Système affiche la liste des UE.
