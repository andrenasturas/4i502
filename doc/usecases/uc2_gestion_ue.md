## UC2 Gérer les UE

* Créé le 06/10/16
* Mis à jour le 16/10/16
* Écrite par Damien Serin
* Version 1.3.0

### Description

La Gestion des UE permet à l'Enseignant d'ajouter, éditer et supprimer des UE.

### Acteur(s) concerné(s)

* Enseignant

### Pré-Conditions

* L'Enseignant est sur la liste des UE.

### Scénario nominal

1. L'Enseignant sélectionne une UE à éditer.
2. Le Système vérifie si l'enseignant est bien le propriétaire de cette UE.
3. Le Système affiche le formulaire d'édition de l'UE.
4. L'Enseignant modifie les champs souhaités.
5. L'Enseignant valide les modifications.
6. Le Sytème notifie l'Enseignant des modifications.

### Post-Conditions

* Le Système a enregistré l'action de l'Enseignant.

### Alternatives possibles

A1. L'Enseignant souhaite ajouter une nouvelle UE.
    1. Cette alternative se déclenche après l'étape 2 du scénario nominal.
    2. Le Système affiche le formulaire d'ajout d'une UE.
    3. L'Enseignant renseigne les champs du formulaire d'ajout d'une UE.
    4. L'Enseignant valide l'ajout de l'UE.
    3. Le Sytème notifie l'Enseignant de l'ajout d'une nouvelle UE.
    4. Le scénario nominal reprend à l'étape 2.

A2. L'Enseignant n'est pas le créateur de l'UE	.
    1. Cette alternative se déclenche après l'étape 4 du scénario nominal.
    2. Le Système affiche un message d'erreur sur l'application web.
    3. Le scénario nominal reprend à l'étape 2.

A3. L'Enseignant souhaite supprimer une UE.
    1. Cette alternative se déclenche après l'étape 5 du scénario nominal.
    2. L'Enseignant clique sur le boutton permettant de supprimer l'UE selectionnée.
    3. Le Système demande à l'enseignant de confirmer la suppression de l'UE.
    4. L'Enseignant confirme la demande de suppression.
    5. Le Système notifie l'Enseignant de la suppression de l'UE.
    6. Le scénario nominal reprend à l'étape 2.

### Exceptions possibles

E1. L'Enseignant annule l'action en cours.
    1. Cette execption se déclenche après l'étape 5 ou 6 du scénario nominal, ou après l'étape 2 ou 3 du scénario alternatif A1, ou après l'étape 3 du scénario alternatif A3.
    2. L'Enseignant clique sur le bouton d'annulation.
    3. Le Système notifie l'enseignant de l'annulation de l'action en cours.
    4. Le Système affiche la liste des UE.
