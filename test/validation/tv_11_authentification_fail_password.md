## TV_11 Authentification échouée (mot de passe invalide)

* Créé le 13/10/16
* Mis à jour le 13/10/16
* Écrite par André Nasturas
* Version 1.0

### Contexte

* L'Utilisateur affiche la page d'authentification l'application web (TV_02).
* Il n'existe pas d'Enseignant enregistré dans le Système dont l'identifiant est **Professeur** et et le mot de passe est **MotDePasseErroné**

### Entrée

* Identifiant **Professeur**
* Mot de passe **MotDePasseErroné**

### Scénario nominal

1. L'Utilisateur tape dans le formulaire d'authentification l'identifiant et le mot de passe, et valide le formulaire.

### Résultat attendu

* Le Système affiche un message d'erreur expliquant que les identifants entrés sont incorrects.
* Le Système affiche à nouveau le formulaire d'authentification.

### Moyens de vérification

* Confirmation visuelle immédiate
