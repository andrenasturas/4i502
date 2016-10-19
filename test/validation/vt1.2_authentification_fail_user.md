## TV_11 Authentification échouée (identifiant invalide)

* Créé le 13/10/16
* Mis à jour le 19/10/16
* Écrite par André Nasturas
* Version 1.1

### Contexte

* L'Utilisateur affiche la page d'authentification l'application web (TV_02).
* Il n'existe pas d'Enseignant enregistré dans le Système dont l'identifiant est **ProfesseurInconnu** et et le mot de passe est **MotDePasse**

### Entrée

* Identifiant **ProfesseurInconnu**
* Mot de passe **MotDePasse**

### Scénario nominal

1. L'Utilisateur tape dans le formulaire d'authentification l'identifiant et le mot de passe, et valide le formulaire.

### Résultat attendu

* Le Système affiche un message d'erreur expliquant que les identifants entrés sont incorrects.
* Le Système affiche à nouveau le formulaire d'authentification.

### Moyens de vérification

* Confirmation visuelle immédiate
* L'accès à la page d'authentification est possible.
* L'accès à la page de gestion des UE est impossible (UC2).
