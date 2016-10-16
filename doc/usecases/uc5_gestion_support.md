## UC5 Gestion des supports

* Créé le 06/10/16
* Mis à jour le 16/10/16
* Écrite par Damien Serin
* Version 1.1.1

### Description

La gestion des supports permet à l'Enseignant d'ajouter, éditer et suppprimer des supports pédagogiques.

### Acteur(s) concerné(s)

* Enseignant

### Pré-Conditions

* Aucune

### Scénario nominal

1. L'Enseignant demande l'affichage de la liste des UE.
2. Le Système affiche la liste des UE.
3. L'Enseignant choisit l'UE et le Chapitre pour lequel il souhaite consulter la liste des supports.
4. L'Enseignant sélectionne un support existant à éditer.
5. Le Système vérifie que l'enseignant est bien le propriétaire du support.
6. Le Système affiche la page d'édition d'un support.
7. L'Enseignant modifie les champs souhaités.
8. L'Enseignant valide les modifications.
9. Le Système notifie l'Enseignant de la modification.

### Post-Conditions

* Le Système a enregistré l'action de l'Enseignant.

### Alternatives possibles

A1. L'Enseignant souhaite ajouter un nouveau support.
    1. Cette alternative se déclenche après l'étape 3 du scénario nominal.
    2. Le Sytème affiche le formulaire d'ajout d'un support.
    3. L'Enseignant renseigne les champs du formulaire d'ajout d'un support.
    4. L'Enseignant valide l'ajout du support.
    5. Le Système notifie l'ajout du support au chapitre souhaité.
    6. Le scénario nominal reprend à l'étape 2.

A2. L'Enseignant n'est pas le propriétaire du support.
    1. Cette alternative se déclenche après l'étape 5 du scénario nominal.
    2. Le Système affiche un message d'erreur sur l'application web.
    3. Le scénario nominal reprend à l'étape 2.

A3. L'Enseignant souhaite supprimer le support sélectionné.
    1. Cette alternative se déclenche après l'étape 6 du scénario nominal.
    2. L'Enseignant clique sur le bouton permettant de supprimer le support sélectionné.
    3. Le Système demande à l'enseignant de confirmer la suppression du support.
    4. L'Enseignant confirme la demande de suppression.
    5. Le Système notifie l'enseignant de la suppression du support.
    6. Le scénario nominal reprend à l'étape 2.

### Exceptions possibles

E1. L'Enseignant annule l'action en cours.
    1. Cette exception se déclanche après l'étape 3, 6 ou 7 du scénario nominal, ou après l'étape 2 ou 3 du scénario alternatif A1, ou après l'étape 3 du scénario alternatif A3.
    2. L'Enseignant clique sur le bouton d'annulation.
    3. Le Système notifie l'enseignant de l'annulation de l'action en cours.
    4. Le Système affiche la liste des UE.
