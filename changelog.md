# 🛠️ Change Log

Tous les changements notables apportés à ce projet seront documentés dans ce dossier.

## ⌛ En cours de traitement

[🎯🎯🎯 Priorité urgente]

[🔥🔥🔥 Priorité haute]
  - **Lenteur plannig atelier** : *Correction de la lenteur d'affichage de l'écran de l'atelier*
  - **Actualisation en direct** : *Changement du mode d'actualisation des filtres*
  - **Erreur ordre visualisation commande** : *L'ordre de visualisation des commandes n'est pas bon*
    
[🔥🔥 Priorité moyenne]
- **Ajout d'une seconde laize** : *Ajout d'une seconde laize pour réserver la bonne quantité de matière dans le stock*
- **Modification du module de temps de travail** : *Modifier l'écran de temps de travail atelier pour prendre en compte la pause-déjeuner*
- **Changement du mode de mise à jour automatique** : *Changement de la mise à jour automatique pour rendre le système plus robuste*
- **Modification de la liste outil** : *Changer le chargement des informations de la liste outil avec un simple clique*
- **Duplication article** : *Ajouter un bouton de duplication des articles*
  
[🔥 Priorité faible]
- **Changement des couleurs des machines dans le planning** : *Changer l'affichage de la couleur des machines dans le planning. La couleur de la machine sera affichée dans le fond à la place d'être la couleur de police*
- **Changer le nom des machines** : *Changer le nom des machines dans toute l'application*

[💧 Non prioritaire]
- **Création du panier des matières** : *Lors de validation d'une commande, si la matière n'est pas disponible et que l'utilisateur le demande, la matière manquante ira dans un panier de "matières à commander"*
- **Création d'un historique des fiches techniques** : *Création d'un module de sauvegarde des versions des fiches techniques avec restauration possible*
- **Mode vacances des machines** : *Création d'un module de vacance pour empêcher toutes saisie (manuelle ou automatique) dans le planning*
- **Connexion automatique** : *Ajouter une connexion automatique avec la saisie du mot de passe toutes les semaines*

## [v1.40.0] - 2025-12-13

### 🆕 Ajouts

- **Déplacement des commandes sur 4 semaines** : *Modification de la simulation pour prendre en compte 4 semaines*
- **Suppression d'une commande planifiée** : *Ajout de la suppression d'une commande qui est planifié. Une fois supprimée, celle-ci revient dans la liste des commandes en attente de planification*
- **Pauses repas dans le planning** : *Ajout de l'effet visuel des pauses repas dans le planning*

### 🔄 Modifications

- **Temps de production restant** : *Changement du libellé d'information qu'une machine ne peut plus produire sur une journée*
  
### ♻️ Corrections

- **Calcul de la disponibilité matière** : *Lors du calcul, la commande en cours de modification était prise en compte dans le calcul de disponibilité et le calcul était érronnée*
- **Impression du BAT avec une fiche techniques** : *Lors de l'impression d'une fiche technique, si le BAT était vide, il était considéré comme indisponible*
- **Impression des fiches techniques** : *Corrections multiples*
- **Déduction du stock** : *La matière n'était pas correctement déduite du stock*
- **Alerte de stock** : *Modification de l'alerte pour une bonne prise en compte du stock*  

## [v1.0.38] - 2025-12-10

### 🆕 Ajouts

- **Alerte de stock matière indisponible** : *Lors de la saisie d'un article dans une commande, une alerte de stock matière indisponible est levé si jamais le stock est indisponible*
- **Alerte lors de la création d'un article avec un produit inexistant** : *Lors de la saisie d'un article dans une commande, si la combinaison laize & produit n'existe pas, alors une alerte est levé et le produit est créé*
- **Ecrans multiples article** : *L'écran des articles peut maintenant afficher plusieurs articles*
- **Impression fiche technique et BAT** : *Ajout de la fusion entre la fiche technique et le BAT*
- **Sélection automatique** : *Lorsqu'un commande est créée, celle-ci est automatiquement sélectionnée dans la liste des commandes*
- **Alerte de création** : *Ajout d'une alerte de création des articles*

### 🔄 Modifications

- **Changement de l'affichage des commandes sans date de planification** : *Ajout d'une colonne code client et changement des libellés de colonnes*
- **Changement icone** : *Changement de l'icone d'ajout d'un article à une commande*
- **Saisie du Z** : *Modification de la liste déroulante du nombre de dents (Z) par une zone de texte*

### ♻️ Corrections

- **Modification d'un BAT** : *Correction des erreurs liées à la modification d'un BAT*
- **Création et modification d'un article** : *Correction des erreurs liées à la création et à la modification d'un article*
- **Calcul article** : *Actualisation des calculs PA HT/1000 et M²/1000 lors de la saisie d'informations d'un article*
- **Actualisation des articles** : *Lors de la création d'un article, la liste des articles n'était pas correctement actualisée*
- **Filtre fiche technique** : *Correction des filtres d'affichage des fiches techniques*

## [v1.0.37] - 2025-12-02  

### 🆕 Ajouts

- **Temps de production restant** : *Ajout du calcul de temps de production restant par machine. ⚠️ Le calcul du temps de production restant est basé sur les commandes saisient et le temps théorique de travail. Le calcul sera adapté lors de la modification du temps de production réel de l'atelier*
- **Bouton vers le changelog** : *Ajout d'un bouton pointant vers le changelog de l'application*
- **Infobulles** : *Des infobulles ont été ajoutées sur l'ensemble des boutons de l'application*


### 🔄 Modifications

- **Sauvegarde du fichier de configuration** : *Le fichier de configuration est maintenant sauvegardé. Le fichier ne sera plus demandé à chaque mise à jour*
- **Masquage d'une colonne ID** : *Dans la liste des fiches techniques, l'ID était visible. Il est maintenant masqué*
- **Ajout d'un article à une commande** : *Le fonctionnement d'ajout d'un article à une commande a évolué. Maintenant, lors de la sélection d'un article, celui-ci est automatiquement ajouté à la commande et est directement modifiable*
- **Filtre liste des articles** : *Le filtre de la liste des articles a été étendu à l'ensemble des colonnes visible dans la liste*
- **Changement de libellé dans la saisie d'une commande** : *Dans l'écran de saisit d'une commande, le champ 'Num. Commande' a été remplacé par 'Référence client' et 'Num. Lot' par 'N° Lot CM'*

### ♻️ Corrections

- **Erreur de mise à jour des suppressions des commandes commandes** : *Lors de la suppression d'une commande, celle-ci pouvait toujours être visible dans la liste des commandes en attente de plannification*
- **Filtre des commandes dans date de plannification** : *Lorsqu'un filtre machine est appliqué sur le planning, celui-ci est également appliqué sur les commandes en attente de plannification*
- **Erreur de saisie de date de livraison** : *Lors de la création d'une commande, la date de départ était automatiquement sauvegardée dans la date de livraison*
- **Numéro de semaines** : *Les numéros de semaines n'étaient pas toujours corrects dans le planning*
- **Liste déroulante des formats de cartons** : *Correction de la liste déroulante des formats qui n'affichait pas la bonne liste*
- **Liste des commandes** : *Dans l'écran de sélection de l'heure de début de production, la colonne Z n'était jamais remise à zéro*

### ⛔ Abandon

- **Modification commentaire** : *La modification directement du commentaire dans la liste du stock n'est pas possible*

## [v1.0.36] - 2025-11-27  

### 🆕 Ajouts

- **Création de l'écran fiches techniques** : *Création de l'écran de visualisation de toutes le fiches techniques*
- **Crétion du nombre de clichés** : *Ajout d'une liste déroulante du nombre de cliché dans la saisie des commandes. Si cette option est utilisée, le temps de calage de la machine est enlevé du temps de production et un durée de cinq minutes par cliché est ajoutée*
- **Changement de couleur global de l'application** : *Changement de la nuance de vert dans l'application [en cours de changement]*
  
### 🔄 Modifications

- **Impression des fiches techniques** : *Modification du lien vers les fiches techniques*
- **Modification de l'écran de saisie des commandes dans le planning** : *Modification de l'interfacde de saisie des commandes dans le planning pour une optimisation du chargement*
  
### ♻️ Corrections

- **Erreur lors de la création d'une commande** : *A la création d'une commande, celle-ci n'avait pas d'état pas défaut. Cela entrainait une erreur lors du placement de la commande dans le planning*
- **Erreur de suppression d'une commande** : *Correction de l'erreur lié à la suppression d'une commannde*
  
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









