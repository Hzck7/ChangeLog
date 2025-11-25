# 🛠️ Change Log

Tous les changements notables apportés à ce projet seront documentés dans ce dossier.

## [En cours de traitement]

[Priorité urgente]

[Priorité haute]
- **Impression des fiches techniques** : *Ajouter le BAT à l'impression*
- **Changement de l'écran des commandes dans le planning** : *Changement du type d'écran de la commande dans le planning pour gagner en rapidité d'exécution*
- **Ajout des infos bulle dans l'ensemble de l'application** : *Ajout des informations d'utilisation à l'utilisateur sur l'ensemble des boutons de l'application*
- **Erreur de liste déroulante "format carton"** : *La liste déroulante du format carton ne charge pas les bonnes données*
- **Étendre l'action de la simulation des commandes** : *Étendre à 4 semaines la simulation de déplacement des commandes*
  
[Priorité moyenne]
- **Ajout d'une seconde laize** : *Ajout d'une seconde laize pour réserver la bonne quantité de matière dans le stock*
- **Modification de la zone commentaire dans l'onglet stock** : *Avoir la possibilité de modifier le commentaire directement dans le tableau*
- **Modification du module de temps de travail** : *Modifier l'écran de temps de travail atelier pour prendre en compte la pause-déjeuner*
  
[Priorité faible]
- **Création du panier des matières** : *Lors de validation d'une commande, si la matière n'est pas disponible et que l'utilisateur le demande, la matière manquante ira dans un panier de "matières à commander"*
- **Changement des couleurs des machines dans le planning** : *Changer l'affichage de la couleur des machines dans le planning. La couleur de la machine sera affichée dans le fond à la place d'être la couleur de police*
- **Création d'un historique des fiches techniques** : *Création d'un module de sauvegarde des versions des fiches techniques avec restauration possible*
- **Mode vacances des machines** : *Création d'un module de vacance pour empêcher toutes saisie (manuelle ou automatique) dans le planning*
- **Connexion automatique** : *Ajouter une connexion automatique avec la saisie du mot de passe toutes les semaines*
  
## [v1.0.35] - 2025-11-25

### 🆕 Ajouts

- **Ajout d'un bouton de stock** : *Ajout d'un bouton pour afficher le stock sur une fenêtre indépendante*
- **Ajout du nombre de dents dans le planning** : *Le nombre de dents a été ajouté dans les informations visualisées dans le planning ainsi que dans l'écran du choix de début de production*

### 🔄 Modifications

- **Sélection automatique d'un article** : *Lors de la sélection d'une commande, le premier article est automatiquement sélectionné et chargé*
- **Changement des couleurs des champs PA €/HT 1000 & M²/1000** : *La couleur verte a été ajoutée pour les données issues du squelette de l'article et la couleur rouge pour les données modifiées*

### ♻️ Corrections

- **Correction de la l'affichage de la liste déroulante des Z la partie commande** : *La liste s'affichait vide peu importe l'article saisit*
- **Changement du lien vers l'image de sens** : *Le lien vers l'image de sens n'allait pas chercher au bon endroit sur le NAS*
- **Erreur sur la mise à jour des prix** : *Une erreur était déclenchée lors de la modification de prix via l'écran "mise à jour des prix"*
- **Erreur lors du changement de mois et d'année dans l'onglet planning** : *Correction de l'erreur de base de données lors du chargement du planning*


