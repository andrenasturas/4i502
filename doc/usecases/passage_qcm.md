## UC Passage d'un QCM

* Créé le 06/10/16
* Mis à jour le 06/10/16
* Écrite par André Nasturas
* Version 1.0

### Description

Le Passage d'un QCM désigne les actions de l'Utilisateur pour générer une série de questions à choix multiple d'une chapitre donnée d'une UE donnée, y répondre successivement, lire les corrections et enfin obtenir une note représnetant le nombre de questions auxquelles pour lesquelles il a choisi la réponse correcte.

### Acteurs concernés

* Utilisateurs

### Pré-Conditions

* Il existe déjà des questions prêtes à être posées à l'Utilisateur.

### Scénario nominal

1. L'Utilisateur accède à l'application web.
2. Le Système affiche la liste des UE existantes.
3. L'Utilisateur choisit l'UE de son choix en cliquant dessus.
4. Le Système affiche la liste des chapitres existantes dans l'UE choisie.
5. L'Utilisateur choisit le chapitre de son choix en cliquant dessus.
6. Le Système affiche un formulaire proposant à l'Utilisateur de générer une séries de questions (QCM).
7. L'Utilisateur choisit un nombre de question (entre 1 et 20) et le tape dans le formulaire, puis valide le formulaire en cliquant sur le bouton adéquat.
8. Le Système choisit aléatoirement le nombre de questions demandé par l'Utilisateur parmi les question existantes dans l'UE et le chapitre choisi.
9. Le Système affiche une question.
10. L'Utilisateur répond à la question en choisissant une des réponses proposées.
11. Le Système enregistre la réponse choisie.
11. Tant qu'il reste des questions non répondues, reprendre le scénario nominal à l'Étape 9.
12. Le Système calcule le nombre de bonne réponses et l'affiche.

### Post-Conditions

Aucune.

### Alternatives possibles

Aucune.

### Exceptions possibles

1. L'utilisateur abandonne le QCM encliquant sur le bouton d'annulation.
    1. Cette exception se déclanche après l'étape 9.
    2. Le Système affiche la page d'accueil.

### Exigences non-fonctionnelles.

Aucune.

