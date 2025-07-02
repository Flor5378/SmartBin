# Projet : Interface de tri de déchets avec poubelles intelligentes en Java

### Exécution du projet

Il s'agit d'un fichier **JAR exécutable**.  
Pour lancer le fichier, il faut appliquer la commande adaptée dans un terminal bash:

```bash

java --module-path "C:\Chemin\vers\javafx\lib" --add-modules javafx.controls,javafx.fxml -jar C:\Chemin\vers\ProjetJavaPoubelle_GARCIA_MARIAU_SMITH_JAFFUEL_GROLLEAU.jar

```
---

### Contenu du projet

- Différentes classes permettant de changer l'état des objets, à savoir :  
  - Gestion des poubelles  
  - Gestion des partenariats  
  - Gestion des points fidélités et des dépôts réalisés

---

### Prise en main de l'interface

Utilisation par la méthode **Point and Click** :

- **Écran d'accueil** : choix du type d'utilisateur  
  - Employé d'un centre de Tri  
  - Ménage (lié à un des centres de Tri)

---

#### Côté Employé

- Accès via différents boutons aux niveaux de remplissage des poubelles dans les centres de tri  
- Gestion des poubelles via le bouton *Gérer les corbeilles* :  
  - Ajout dans un centre de tri  
  - Visualisation des données  
  - Vidage des poubelles  
- Gestion des contrats de partenariats entre centres de tri et commerces via *Gérer les partenariats*  
  - Possibilité d'ajouter ou de prolonger des partenariats via les boutons annexes

---

#### Côté Utilisateur (Ménage)

- Identification requise pour accéder à l’interface du centre de Tri  
- La liste des IDs valides des ménages est affichée dans la console  
- Une fois authentifié, possibilité de réaliser un dépôt :  
  - Spécifier le type de déchet  
  - Indiquer la quantité (en kilogrammes)  
- Page *Mon Compte* affichant :  
  - Adresse  
  - Nom  
  - Points fidélités obtenus  
- Les points fidélités s’incrémentent à chaque dépôt  
- Utilisation des points fidélités via le bouton *Convertir mes points de fidélité* qui ouvre une page permettant :  
  - Visualiser ses points fidélités  
  - Les convertir en bons d’achats ou réductions en sélectionnant les commerces partenaires

---

