## TV_22 supprimer une UE

* Créé le 19/10/16
* Mis à jour le 19/10/16
* Écrite par Sandra Laduranti
* Version 1.0

### Contexte

* L'Utilisateur affiche la page de l'UE.
* Il existe une UE enregistrée dans le Système dont le nom est **4I502**
* Il existe un Enseignant enregistré dans le Système dont l'identifiant est **Professeur** et étant le possesseur de l'ue **4I502**

### Entrée

* aucune

### Scénario nominal

1. L'Enseignant selectionne la modification de l'UE.
2. L'Enseignant selectionne ensuite la suppression de l'UE.
3. L'Enseignant confirme à deux reprises la suppression de l'UE.

### Résultat attendu

* Le Système affiche une confirmation de suppresion de l'UE, l'UE a été supprimée.


### Moyens de vérification

* Confirmation visuelle immédiate, l'UE n'apparait plus sur l'interface
* Si accès à base de donnée, vérification de l'absence de l'UE dans celle-ci
* Recréer l'UE au même nom que celle supprimée
