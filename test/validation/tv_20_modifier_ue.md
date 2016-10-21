## VT2.0 Modifier une UE

* Créé le 19/10/16
* Mis à jour le 21/10/16
* Écrite par Sandra Laduranti
* Version 1.1.0

### Contexte

* L'Enseignant affiche la page de l'UE.
* Il existe une UE enregistrée dans le Système dont le nom est **4I502**.
* Il existe un Enseignant enregistré dans le Système dont l'identifiant est **Professeur** et étant le possésseur de l'ue **4I502**.
* Il n'existe pas d'UE enregistrée dans le Système dont le nom est **4I503**.

### Entrée

* Nouveau nom **4I503**

### Scénario nominal

1. L'Enseignant sélectionne la modification de l'UE et rentre le nouveau nom **4I503**.
2. L'Enseignant confirme.

### Résultat attendu

* Le Système affiche une confirmation de modification de l'UE, l'UE a été mise à jour.

### Moyens de vérification

* Confirmation visuelle immédiate.
* L'affichage de la liste des UE (VT1.0) montre l'absence d'UE appelée **4I502**, mais montre bien l'UE **4I503**.
* L'affichage de l'UE **4I503** (TV2.0) montre qu'il s'agit bien de la même UE (mêmes chapitres, même propriétaire).
