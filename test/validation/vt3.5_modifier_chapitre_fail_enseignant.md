## VT3.5 Modifier chapitre (enseignant n'est pas le créateur du chapitre)

* Créé le 19/10/16
* Mis à jour le 21/10/16
* Écrite par Sandra Laduranti
* Version 1.0.1

### Contexte

* L'Enseignant affiche la liste des chapitres.
* Il existe une UE **4I502** enregistrée dans le système.
* Il existe un chapitre **chap1** dans l'UE **4I502**.
* Il existe un Enseignant enregistré dans le Système dont l'identifiant est **Professeur** et n'étant pas le possesseur de l'ue **4I502**.

### Entrée

* Nouveau nom **chap1.1**
* Nouvelle description **Ceci est le chapitre 1**

### Scénario nominal

1. L'Enseignant sélectionne la modification du chapitre.

### Résultat attendu

* Le Système affiche un message d'erreur notifiant l'interdiction d'accès à la modification du chapitre par l'Enseignant.

### Moyens de vérification

* Confirmation visuelle immédiate.
* L'Enseignant n'a pas accès à la page de modification du chapitre.

