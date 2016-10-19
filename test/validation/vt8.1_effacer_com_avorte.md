## VT8.1 Suppression d'un commentaire avorté

* Créé le 13/10/16
* Mis à jour le 13/10/16
* Écrite par André Nasturas
* Version 1.0

### Contexte

* L'Enseigannt est authentifié sur le Système (TV_10).
* Un Enseignant a créé une UE **UETest** (TV_20), dans laquelle il a créé un chapitre **C1** (TV_30), dans laquelle il a créé une question **Q1** (TV_40).
* Un Utilisateur a posté un commentaire sur la question **Q1** (TV_70)
* L'Enseignant affiche la page de la question **Q1** (TV_61)

### Entrée

* Aucune

### Scénario nominal

1. L'Enseignant utilise l'option de suppression du commentaire de la question **Q1**.
2. L'Enseignant annule son action lorsque le Système lui demande de confirmer son choix.

### Résultat attendu

* Aucun changement.

### Moyens de vérification

* Le commentaire ciblé reste affiché sur la page de la question **Q1**, et il est possible de tenter à nouveau de le supprimer (TV_80).
