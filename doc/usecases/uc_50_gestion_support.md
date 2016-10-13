## UC_50 Gestion des supports

* Créé le 06/10/16
* Mis à jour le 06/10/16
* Écrite par André Nasturas
* Version 1.1

### Description

L'Authentification permet à l'Utilisateur de s'identifier en tant qu'Enseignant et d'accéder aux fonctionnalités limitées de l'application, comme la gestion des UE et des questions.

### Acteurs concernés

* Utilisateur

### Pré-Conditions

* Aucune

### Scénario nominal

1. L'Utilisateur clique sur le bouton d'authentification sur l'application web.
2. Le Système affiche le formulaire de connexion.
3. L'Utilisateur entre son identifiant et son mot de passe dans le formulaire.
4. L'Utilisateur clique sur le bouton de validation.
5. Le Système vérifie l'exactitude des identifiant et mot de passe.
6. Le Système affiche la page de gestion reservée aux Professeurs sur l'application web.

### Post-Conditions

* L'enseignant a accès à la page de gestion lui étant reservée.

### Alternatives possibles

1. Les identifiants fournis par l'Utilisateur sont incorrects.
    1. Cette alternative se déclanche après l'étape 5 du scénario nominal.
    2. Le Système affiche un message d'erreur sur l'application web.
    3. Le scénario nominal reprend à l'étape 2.

### Exceptions possibles

2. L'Utilisateur ne souhaite plus se connecter.
    1. Cette exception se déclanche après l'étape 2.
    2. L'Utilisateur clique sur le bouton d'annulation.
    3. Le Système affiche la page d'accueil de l'application web.
