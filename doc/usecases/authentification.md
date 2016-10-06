## UC Authentification

* Créé le 06/10/16
* Mis à jour le 06/10/16
* Écrite par André Nasturas
* Version 1.0

### Description

L'Authentification permet à l'Utilisateur de s'identifier en tant qu'Enseignant et d'accéder aux fonctionnalités limitées de l'application, comme la gestion des UE et des questions.

### Acteurs concernés

* Utilisateur

### Pré-Conditions

* L'Utilisateur possède un compte enregistré dans le Système

### Scénario nominal

1. L'Utilisateur clique sur le bouton d'authentification sur l'application web.
2. Le Système affiche le formulaire de connexion.
3. L'Utilisateur entre son identifiant et son mot de passe dans le formulaire, puis clique sur le bouton de validation.
4. Le Système vérifie l'exactitude des identnfiant et mot de passe.
5. Le Système affiche la page de gestion des UE reservée aux Professeurs sur l'application web.

### Post-conditions

Aucune.

### Alternatives possibles

1. Les identifiants fournis par l'Utilisateur sont incorrects.
    1. Cette alternative se déclanche après l'étape 4 du scénario nominal.
    2. Le Système affiche un message d'erreur sur l'application web.
    3. Le scénario nominal reprend à l'étape 2.

### Exceptions possibles

2. L'Utilisateur ne souhaite plus se connecter.
    1. Cette exception se délcanche après l'étape 2.
    2. L'Utilisateur clique sur le bouton d'annulation.
    3. Le Système affiche la page d'accueil de l'application web.

### Exigences non-fonctionnelles

Aucune.
