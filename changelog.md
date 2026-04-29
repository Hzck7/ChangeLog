# 🛠️ Journal des modifications

Tous les changements notables apportés à ce projet seront documentés dans ce dossier.
## [v1.60.2] - 2025-04-29
### ♻️ Corrections
- ESA-92 | Correction de l'erreur d'ajout de quantité en stock
- ESA-93 | Correction de l'erreur de validation de la matière lors d'une fin de production
## [v1.60.1] - 2025-04-29
### 🆕 Ajouts 
- ESA-80 | Export des fiches techniques vers un fichier Excel
- ESA-83 | Le format des cartons n'est plus un champ obligatoire
- ESA-88 | Ajout du nom du client et du format dans la visualisation des mouvements de stock
### 🔄 Modifications 
- ESA-79 | Actualisation de la liste des commandes lorsque le filtre des clients est vide
- ESA-81 | Changement du fonctionnement du filtre de recherche des clients dans les fiches techniques
- ESA-82 | Modification du filtre des machines pour les fiches techniques
- ESA-84 | Modification de l'infobulle des commandes dans le planning
### ♻️ Corrections
- ESA-83 | Correction du chargement de l'image de sens de sortie
- ESA-91 | Correction de l'erreur de calcul du prix de la plaque
- ESA-90 | Correction du troncage de la laize matière
## [v1.60.0] - 2025-04-28
### 🆕 Ajouts 
- **Génération des devis** : *Mise à jour de la génération des devis*
## [v1.55.9] - 2025-04-28
### 🆕 Ajouts 
- **Génération des devis** : *Mise à jour de la génération des devis*
## [v1.55.8] - 2025-04-27
### 🆕 Ajouts 
- **Génération des devis** : *Mise à jour de la génération des devis*
## [v1.55.7] - 2025-04-27
### 🆕 Ajouts 
- **Génération des devis** : *Mise à jour de la génération des devis*
## [v1.55.6] - 2025-04-23
### 🆕 Ajouts 
- **Génération des devis** : *Mise à jour de la génération des devis*
## [v1.55.5] - 2025-04-22
### 🆕 Ajouts 
- **Génération des devis** : *Mise à jour de la génération des devis*
## [v1.55.4] - 2025-04-20
### 🔄 Modifications 
- **Filtre fiches techniques** : *Modification de la liste des filtres dans les fiches techniques*
### ♻️ Corrections
- **Affichage commentaire client** : *Affichage du commentaire client*

## [v1.55.3] - 2025-04-20
### 🆕 Ajouts 
- **Ajout colonne stock** : *Ajout de la colonne et du filtre fournisseur*
- **Modification informations** : *Modification des informations de stock maintenant possible*
### ♻️ Corrections
- **Information stock** : *Lors de l'ajout d'une nouvelle ligne dans le stock, si le libellé de la ligne avait une apostrophe, la ligne rentrait en erreur*
- **Sélection de la laize stock** : *Correction de l'erreur de sélection de laize dans le stock*
- **Actualsiation planning** : *Correction de l'erreur d'actualisation des commandes sans date de plannification*
## [v1.55.2] - 2025-04-15
### ♻️ Corrections
- **Calcul du temps de production** : *Le temps de production n'était plus correctement calculé*
- **Ouverture semaine** : *Changement de la gestion des semaines dans l'ouverture des machines*
## [v1.55.1] - 2025-04-13
### 🆕 Ajouts 
- **Visualisation fiche technique** : *La fiche technique est maintenant visualisable lors d'un double clique*
- **Vérification plaque** : *Lors de la saisie d'une commande, une vérification de la plaque est faite.*
- **Plage dynamique** : *Ajout des plages dynamiques dans la gestion des horaires de production de machine*
- **Suppression sélection** : *Il n'y a plus qu'une seule commande sélectionnable dans le planning*

### 🔄 Modifications 
- **Recherche fiche technique** : *Lors de la recherche de fiche technique, la sélection de fiche pour impression est automatiquement désélectionné*
- **Infobulle planning** : *Modification des informations de l'infobulle planning*
  
## [v1.55.0] - 2025-04-07
### ♻️ Corrections
- **Affichage caractères observation** : *Dans le champ observation d'un article, des caractères non sollicités étaient affichés. Le problème intervenait lors de la sauvegarde à cause d'un champ mal dimensionné*
- **Créneaux commande** : *Modification de l'affichage des créneaux interdit dans le placement d'une commande*
- **Plage horaire nouveau planning** : *Correction de l'erreur de plage horaire dans le nouveau planning*
## [v1.54.4] - 2025-03-26
### 🆕 Ajouts 
- **Génération des devis** : *Ajout du module de génération des devis en version alpha*
### 🔄 Modifications 
- **Infobulle commandes** : *Retrait de l'infobulle des commandes*
### ♻️ Corrections
- **Impression étiquettes rouleaux** : *Correction de l'erreur de champ dans les étiquettes rouleaux*
## [v1.54.3] - 2025-03-20
### 🆕 Ajouts 
- **Laize matière** : *Ajout de la laize matière dans le fichier Excel des clichés*
### ♻️ Corrections
- **Modification d'un article** : *Correction de l'erreur lors de la validation d'un article*
- **Erreur de format** : *Correction de l'erreur de format lors du chargement d'un article*
## [v1.54.2] - 2025-03-19
### 🔄 Modifications 
- **Nouveau planning** : *Réactivation du nouveau planning uniquement en consultation* 
## [v1.54.1] - 2025-03-18
### 🆕 Ajouts 
- **Filtre automatique** : *Au lancement de l'application, les commandes sont automatiquement filtrées sur l'état "en attente" ou "en production"*
### ♻️ Corrections
- **Affichage simulation** : *Les commandes terminées n'étaient pas toutes masquées lors de la simulation*
## [v1.54.0] - 2025-03-17
### 🆕 Ajouts 
- **Version préprod** : *Ajout de la version de préproduction pour des tests sur le nouveau planning*
## [v1.53.4] - 2025-03-17
### 🆕 Ajouts 
- **Infobulle commandes** : *Ajout d'une infobulle au survol des commandes*
- **Filtre commandes** : *Ajout d'un filtre des états des commandes*
- **Mise en forme champ observation** : *Le champ  observation peut être mis en forme par du texte en gras et en couleur*
### ♻️ Corrections
- **Mise à jour ML. Prod** : *Mise à jour de la quantité de ML prod lors de changement dans le squelette de l'article* 
## [v1.53.3] - 2025-03-12
### ♻️ Corrections
- **Mise à jour automatique** : *La mise à jour automatique ne se lançait plus correctement*
- **Etiquettes rouleaux** : *Corrections des erreurs de mappage des champs dans les étiquettes rouleaux*
## [v1.53.2] - 2025-03-11
### ♻️ Corrections
- **Affichage info bulle** : *Correction de l'erreur d'affichage de l'info bulle dans le planning*
- **Informations étiquettes cartons** : *Corretion des informations dans les étiquettes cartons*
## [v1.53.1] - 2025-03-11
### ♻️ Corrections
- **Erreur nom imprimantes** : *Erreur sur le paramètrage des noms d'imprimantes*
## [v1.53.0] - 2025-03-11
### 🆕 Ajouts 
- **Connexion automatique** : *Ajout de l'option de connexion automatique et de déconnexion*
- **Info bulle planning** : *Ajout dans l'info bulle du planning la quantitée d'étiquettes*
### 🔄 Modifications 
- **Impressions des étiquettes** : *Refonte de l'impression des étiquettes*

## [v1.52.4] - 2025-03-09
### 🆕 Ajouts 
- **Info bulles planning** : *Ajout d'une info-bulle lors du passage du curseur sur une commande*
### 🔄 Modifications 
- **Caclul aplat** : *Modification du calcul du temps de production avec un aplat*
### ♻️ Corrections
- **Visualisation des commandes dans l'atelier** : *Certaines commandes n'étaient pas visibles dans l'atelier*
- **Lenteur chargement atelier** : *Optimisation de l'affichage du planning atelier*
- **Erreur PA** : *Modification du format du champ PA et réctification des données dans la table*
- **Déduction du stock** : *Lors de la déclaration de la matière après la production, la matière appelée n'était pas la bonne. Le changement de matière entraînait une erreur de déclaration*
- **Affichage stock** : *Lors de la création d'une nouvelle matière, si celle-ci n'était pas utilisée dans une commande, elle n'apparaissait pas dans le stock*
## [v1.52.2] - 2025-02-26
### 🆕 Ajouts
- **Observation client** : *Ajout du champ 'observation client' dans la fiche technique*
- **Planification des commandes** : *Affichage des commandes en attente*
### ♻️ Corrections
- **Changement de clichés** : *Enregistrement automatique du changement de clichés avec une bonne prise en compte lors de la planification*
- **Affichage des heures de pause** : *Récupération de l'affichage des heures de pauses*
- **Liste outil** : *Application de la date du jour en automatique dans tous les scénarios possible*
## [v1.52.1] - 2025-02-24
### ♻️ Corrections
- **Affichage des heures de pause** : *Récupération de l'affichage des heures de pauses*
- **Erreur aplat** : *La sélection d'un article dans une commande ainsi que la modification de celui-ci ne déclenche plus l'erreur d'aplat*
- **Actualisation des commandes sans dates** : *Modification de l'actualisation de la liste des commandes sans date de modification*
  
## [v1.52.0] - 2025-02-23
### 🆕 Ajouts
- **Double ligne planning** : *Affichage des informations sur deux lignes dans le nouveau planning*
- **Refonte visuels commandes** : *Refonte visuels des segments des commandes*
- **Code couleurs états** : *Changemnent des couleurs des commandes pour afficher les états sous forme de couleur*
- **Changement de cliché** : *Changement du nombre de clichés directement dans la liste des commandes en attente de planification*
- **Changement d'aplat** : *Ajout d'un changement d'aplat : 20 minutes supplémentaires en cas de changement*
- **Verrouillage du planning** : *Ajout d'un bouton de verrouillage du planning* 

### 🔄 Modifications 
- **Modification filtre état** : *Changement de l'affichage des filtres des états*
## [v1.51.1] - 2025-02-18
### 🔄 Modifications 
- **Affichage du bouton nouveau planning** : *Le bouton du nouveau planning est maintenant disponible pour tout le monde*
## [v1.51.0] - 2025-02-18
### 🆕 Ajouts
- **Mise en place du nouveau planning** : *Mise à disposition du nouveau planning en version bêta*
- **Détail du reservé** : *Ajout de la colonne référence client*
  
### 🔄 Modifications 
- **Limitation du nombre de caractères** : *Lors de l'impression d'une étiquette carton, les caractères sont limités lors de l'impression*
  
## [v1.50.3] - 2025-02-12
### 🔄 Modifications
- **Couleur application** : *Harmonisation des couleurs de l'application*

### ♻️ Corrections
- **Date automatique mouvement** : *Lors de la saisie d'un mouvement dans le stock, la date du mouvement est automatiquement rajoutée*
- **Affichage mouvement de stock** : *Correction de l'affichage de multiréférences dans le mouvement de stock*
   
## [v1.50.2] - 2025-02-11
### ♻️ Corrections
- **Correction erreur planification** : *Corrections d'erreurs qui perturbaient la planification*

## [v1.50.1] - 2025-02-11
### ♻️ Corrections
- **Messages d'erreurs** : *Corrections des messages d'erreur lors de la planification*
- **Erreur des heures** : *Correction de l'affichage des heures dans le planning*
- **Erreur chargement des commandes** : *Correction de l'erreur de chargement dans le planning au moment de planifier une commande*
- **Affichage des plages interdites** : *Les plages interdites sont de nouveaux affichées*

## [v1.50.0] - 2025-02-10
### 🆕 Ajouts
- **Export Excel du temps de production** : *Eportation du tableau des temps de production au format Excel*
- **Contrôle du Z** : *Ajout d'un indicateur quand une combinaison cylindre/machine n'existe pas*
    
### 🔄 Modifications
- **Fonction de calcul du temps de production restant** : *Modification de la fonction de calcul du temps de production. Prise en compte réel du temps de production de chacune des commandes*
- **Modification filtre machines** : *Evolution du filtre des machines dans l'écran des temps de production*

### ♻️ Corrections
- **Déplanification commande** : *Lors du changement de la machine depuis une commande, la commande initialement planifiée sera déplanifiée*
- **Affichage des colonnes** : *L'affichage des colonnes dans le planning ne nécessite plus de rafraichissement pour être correctement affiché*
  
## [v1.49.6] - 2025-02-09
### ♻️ Corrections
- **Affichage des commandes** : *Les commandes après 16h30 n'étaient pas correctement affichées*
  
## [v1.49.5] - 2025-02-09
### ♻️ Corrections
- **Planification après 16h30** : *La planification après 16h30 sur la semaine du 09/02/2026 au 13/02/2026 n'était pas possible*
  
## [v1.49.4] - 2025-02-06
### 🆕 Ajouts
- **Ouverture de plannification** : *Pour la semaine du 09/02/2026 au 13/02/2026, la machine markandy est planifiable de 05h00 à 22h00*

## [v1.49.3] - 2025-02-03
### ♻️ Corrections
- **Affichage des commandes en attente** : *Dans l'atelier, certaines commandes en attente n'était pas correctement affichée*
  
## [v1.49.2] - 2025-02-03
### 🆕 Ajouts
- **Bouton rafraîchir** : *Ajout d'un bouton pour rafraîchir la liste des commandes sans date de planification*

### ♻️ Corrections
- **Erreur d'impression des fiches techniques** : *Lors de l'impression de plusieurs fiches techniques, un message d'erreur pouvait apparaitre*
- **Visualisation BAT** : *Le BAT est de nouveau consultable depuis l'espace des commandes*
- **Date de départ** : *Affichage d'une date vide dans le planning sur la date de départ n'est pas renseignée*

## [v1.49.1] - 2025-01-29
### 🆕 Ajouts
- **Bouton stock** : *Ajout d'un bouton de stock sur l'écran de planification*
- **Sélection automatique**  : *Lors de l’utilisation des menus contextuelle dans les tableaux, l’appui sur un clique droit sélectionne automatiquement la ligne*
- **Ajout de colonne** : *Dans la liste des commandes, la date de saisie de la commande a été ajoutée*
- **Opérateur de bobinage** : *Il existe maintenant un opérateur de bobinage dans le suivi des commandes*
- **Filtre des colonnes** : *Ajout d'un filtre de sélection des colonnes dans l'écran de temps de production*
  
### 🔄 Modifications
- **Fiche technique** : *Modification de la trame de la fiche technique*
- **Actualisation ML** : *Actualisation du ML si le nombre d'étiquettes par rouleaux est modifié*

### ♻️ Corrections
- **Correction filtre article** : *Le filtre du libellé de l'article ne fonctionnait plus depuis la dernière mise à jour*
- **Erreur format fiche technique** : *Correction de l'erreur de format lors de l'impression d'une fiche technique client*
- **Mauvaise fiche technique - impression multiple** : *Lors de l'impression multiple, la fiche technique imprimée n'était pas la fiche technique client*
- **Inversion des colonnes** : *Dans le temps de production, deux colonnes étaient inversées*
    
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





































