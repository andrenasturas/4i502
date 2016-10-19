## TV_10 Authentification réussie

* Créé le 13/10/16
* Mis à jour le 19/10/16
* Écrite par André Nasturas
* Version 1.1

### Contexte

* L'Utilisateur affiche la page d'authentification l'application web (TV_02).
* Il existe un Enseignant enregistré dans le Système dont l'identifiant est **Professeur** et et le mot de passe est **MotDePasse**

### Entrée

* Identifiant **Professeur**
* Mot de passe **MotDePasse**

### Scénario nominal

1. L'Utilisateur tape dans le formulaire d'authentification l'identifiant et le mot de passe, et valide le formulaire.

### Résultat attendu

* Le Système affiche un message de bienvenue.
* L'Utilisateur devient un Enseignant.
* L'Enseignant accède à la page de gestion des UE sur l'application web.

### Moyens de vérification

* Confirmation visuelle immédiate.
* L'accès à la page d'authentification est impossible.
* L'accès à la page de gestion des UE est possible (UC2).
