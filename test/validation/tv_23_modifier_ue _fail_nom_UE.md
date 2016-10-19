## TV_23 modification ue échoue (nom déjà existant)

* Créé le 19/10/16
* Mis à jour le 19/10/16
* Écrite par Sandra Laduranti
* Version 1.0

### Contexte

* L'Enseignant affiche la page de l'UE.
* Il existe une UE enregistrée dans le Système dont le nom est **4I502**.
* Il existe un Enseignant enregistré dans le Système dont l'identifiant est **Professeur** et étant le possesseur de l'ue **4I502**.
* Il existe une UE enregistrée dans le Système dont le nom est **4I503**.

### Entrée

* Nouveau nom **4I503**

### Scénario nominal

1. L'Enseignant selectionne la modification de l'UE et rentre le nouveau nom.
2. L'Enseignant confirme.

### Résultat attendu

* Le Système affiche un message d'erreur expliquant que le nouveau nom est déjà présent dans la base et est donc incorrect car doit être unique.
* Le Système affiche à nouveau le formulaire de modification de l'UE.


### Moyens de vérification

* Confirmation visuelle immédiate
* Si accès à base de donnée, nom de l'UE non modifié

