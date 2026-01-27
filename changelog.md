# 🛠️ Change Log

Tous les changements notables apportés à ce projet seront documentés dans ce dossier.

## ⌛ En cours de traitement

[🎯🎯🎯 Priorité urgente]

[🔥🔥🔥 Priorité haute]
  - **Actualisation en direct** : *Changement du mode d'actualisation des filtres*
    
[🔥🔥 Priorité moyenne]
- **Ajout d'une seconde laize** : *Ajout d'une seconde laize pour réserver la bonne quantité de matière dans le stock*
- **Modification du module de temps de travail** : *Modifier l'écran de temps de travail atelier pour prendre en compte la pause-déjeuner*
  
[🔥 Priorité faible]
- **Changer le nom des machines** : *Changer le nom des machines dans toute l'application*

[💧 Non prioritaire]
- **Création du panier des matières** : *Lors de validation d'une commande, si la matière n'est pas disponible et que l'utilisateur le demande, la matière manquante ira dans un panier de "matières à commander"*
- **Création d'un historique des fiches techniques** : *Création d'un module de sauvegarde des versions des fiches techniques avec restauration possible*
- **Mode vacances des machines** : *Création d'un module de vacance pour empêcher toutes saisie (manuelle ou automatique) dans le planning*
- **Connexion automatique** : *Ajouter une connexion automatique avec la saisie du mot de passe toutes les semaines*
  
## [v1.49.1] - 2025-01-27
### 🆕 Ajouts
- **Bouton stock** : *Ajout d'un bouton de stock sur l'écran de planification*
  
### 🔄 Modifications
- **Fiche technique** : *Modification de la trame de la fiche technique*
- **Actualisation ML** : *Actualisation du ML si le nombre d'étiquettes par rouleaux est modifié*

### ♻️ Corrections
- **Correction filtre article** : *Le filtre du libellé de l'article ne fonctionnait plus depuis la dernière mise à jour*
  
## [v1.49.0] - 2025-01-26

### 🆕 Ajouts
### 🔄 Modifications
- **Changement de machine** : *Lors du changement d'une machine, la planification de la commande est supprimée*
### ♻️ Corrections
- **Affichage des commandes planning** : *Sélection des éléments des commandes désormais impossible*
- **Affichage ML atelier** : *Correction de la valeur des ML pour l'atelier*
    
## [v1.48.1] - 2025-01-21

### 🆕 Ajouts
- **Ajout des couleurs machine** : *L'affichage du planning a été modifié pour faire apparaître les couleurs des machines*
- **Ajout du temps de bobinage** : *Ajout du temps de bobinage dans l'écran de temps de production*
- **Suppression de la matière** : *La suppression de la matière est disponible depuis l'écran de mise à jour du prix matière*

### ♻️ Corrections
- **Correction affichage commande** : *En fonction des critères de filtre, les commandes n'étaient pas toujours affichées dans l'ordre d'heure de début dans le planning*
- **Actualisation commande** : *Lors de la modification de l'état d'une commande, l'écran se met correctement à jour*
  
## [v1.48.0] - 2025-01-20

### 🆕 Ajouts
- **Date automatique** : *Lors de la création d'un nouveau format, la date de création est automatiquement ajoutée*
- **Affichage d'Excel** : *Lors de la génération du fichier Excel de cliché, la fenêtre Excel s'ouvre au premier plan*
- **Affichage des commandes sans date de planification** : *L'écran des commandes sans date de planification est maintenant affiché automatiquement sur le deuxième écran*
- **Bouton RAZ filtres** : *Ajout d'un bouton de remise à zéro des filtres sur les formulaires*
- **Changement du comportement de la fenêtre d'impression** : *Après l'impression d'étiquettes, la fenêtre d'impression ne se ferme plus automatiquement*
  
### 🔄 Modifications
- **Modification de format** : *Modification de l'affichage des champs ESP DEV et Laize avec deux chiffres après la virgule.Modification de l'affichage du champ ECH dans la fiche technique*
- **Affichage de la date d'impression dans la fiche technique** : *La date du jour d'impression est maintenant imprimée dans la fiche technique*
- **Modification du comportement du changement d'état de commande** : *Lors du changement d'état d'une commande, les questions de validation ont été supprimées et la fenêtre se ferme automatiquement après*
  
### ♻️ Corrections
- **Affichage du développé dans l'impression de cliché** : *Lors de la demande d'impression du fichier Excel de cliché, le développé n'était pas reprit*
- **Problème mappage du champ ESP DEV** : *Dans la boite à outil, le champ ESP était mal mappé. Il a été supprimé et le mappage a été contrôlé*
- **Couleur pour les commandes terminées** : *La couleur des commandes terminées est correctement affichée dans l'écran de planification d'une commande*
- **Sens de sortie non visible** : *Lors de la modification d'un article, l'image du sens de sortie n'était pas visible*
- **Erreur d'actualisation** : *Correction de l'erreur d'actualisation qui laissait des articles visible sans commande sélectionnée*
- **Suppression d'un client** : *Remise en fonctionnement de la suppression d'un client via le bouton supp*
- **Filtre pause atelier** : *Correction du fonctionnement du filtre pause*
  
## [v1.47.4] - 2025-01-13

### 🔄 Modifications
- **Modification des listes déroulantes** : *Les listes déroulantes sont maintenant actualisées lors de modification sur d'autres plannings*
- **Prise en compte de la laize mini** : *Lors de la création d'un article, la laize mini est maintenant utilisée à la place de la laize 2*
- **Modification taille** : *Réduction de la taille de la fenêtre de stock*

### ♻️ Corrections
- **Erreur lors de la création d'un stock** : *Correction lors de la création d'un article depuis le stock sans quantitée renseignée*
- **Tri des tableaux** : *Le tri des colonnes dans les tableaux fonctionne sur toutes les colonnes*
  
## [v1.47.3] - 2025-01-13

### 🔄 Modifications
- **Commandes terminées** : *lorsqu'une commande est terminée, celle-ci s'affiche d'une couleur différente dans la planification*
- **Liste déroulante** : *Dans l'écran de planification des commandes, la molette ne modifie plus les liste déroulante*

## [v1.47.2] - 2025-01-12

### 🔄 Modifications
- **Réduction du planning** : *Lors de l'impression d'étiquettes, le planning était automatiquement réduit*
- **Affichage de la fenêtre des commandes** : *Certaine fois, la fenêtre des commandes n'était pas affichée au premier plan*

## [v1.47.1] - 2025-01-12

### 🆕 Ajouts
- **Ajout de la laize 2** : *Dans l'écran de saisie d'une commande, ajout du champ laize 2 issue de la liste outil*
- **Actualisation planning** : *Ajout de l'actualisation du planning dans la routine d'actualisation globale*
- **Ajout du filtre code article client** : *Ajout du filtre dans la recherche de fiche technique*
- **Création fiche technique client** : *Création de la fiche technique client a partir de l'ancien modèle*
- **Ajout d'un bouton cocher/décocher** : *Ajout d'un bouton pour sélectionner ou de sélectionner les colonnes des fiches techniques*

### 🔄 Modifications
- **Modification de l'utilisation du filtre des états** : *Dans le planning de l'atelier, le filtre multiple des états a été remplacé par un mono filtre*
- **Contrôle du stock** : *L'affichage de la pastille de couleur n'était pas cohérent avec le stock réel de l'atelier*
- **Optimisation de l'affichage** : *Dans le planning de l'atelier, après une validation de commande, le temps de chargement du planning a été réduit*
- **Modification des filtres stock** : *Ajout de la possibilité de trié le stock avec des valeurs > et <*
- **Modification format laize mini** : *Retrait des 3 chiffres après la virgule de la laize mini dans la liste outil*
  
### ♻️ Corrections
- **Remise dans l'ordre des commandes** : *Dans le planning de l'atelier, les commandes sont maintenant affichées par ordre de début de production*
- **Erreur de mise à jour du prix** : *Correction de l'erreur de format rencontré dans la mise à jour des prix*
- **Erreur de calcul - temps de production restant** : *Correction de l'affichage du temps de production restant*
- **Rechargement de la table des prix** : *Correction des erreurs de prix matière*
- **Corrections multiples en run**
  
## [v1.40.0 -> v1.46.1]

- **Corrections multiples en run**

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

















