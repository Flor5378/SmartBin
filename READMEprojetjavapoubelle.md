# Implémentation d'une interface permettant le tri de déchets grâce à des poubelles intelligentes en Java.


## Présentation succincte des composantes du projet :

Il s'agit d'un fichier JAR exécutable.
Pour run le fichier il faut apliuer la commande adaptée dans le md: java --module-path "C:\Chemin\vers\javafx\lib" --add-modules javafx.controls,javafx.fxml -jar C:\Chemin\vers\ProjetJavaPoubelle_GARCIA_MARIAU_SMITH_JAFFUEL_GROLLEAU.jar
   - Dans celui-ci nous avons différentes classes, desquelles découlent nos méthodes qui permettent de changer l'état de nos objets à savoir: la gestion des poubelles, des partenariats et la gestion des points fidélités ainsi que les dépôts réalisés.
 
   - Pour prendre en main l'interface, il suffit d'utiliser la méthode Point and Click: on choisit initialement au niveau de l'écran d'accueil notre type d'utilisateur: Employé d'un centre de Tri ou un Ménage (lié à un des centres de Tri).
       
       1. Côté Employé, on a accès via différents boutons aux niveaux de remplissage des différentes poubelles des différents centres de tris. De plus on accède par le bouton gérer les corbeilles, à la gestion des poubelles: leur ajout dans un centre de tri, leurs données ainsi qu'une bouton pour les vider. On a également accès aux termes des contrats de partenariats entre les centres de tri et des commerces dans la rubrique: "Gérer les partenariats". On peut en ajouter ou en prolonger via les boutons annexes.
     
       2. Côté une utilisateur. L'utilisation de l'interface du centre de Tri par les Ménages requiert tout d'abord une identification. La liste des id des ménages valides est toujours donnée dans la console. Une fois l'authentification réalisée le ménage a la possibilité de réaliser un dépôt dont il spécifie le type de déchet ainsi que la quantité (en kilogs). Par ailleurs la page Mon Compte lui indique son adresse, son nom ainsi que les points fidélités déjà obtenu. A chaque dépôt réalisé, il incrémente d'une certaine valeur ses points fidélite. Ceux-ci peuvent utilisés grâce au bouton: "Convertir mes points de fidélité" qui affiche une page dans laquelle le ménage peut: 
        - Voir ses points de fidélités.
        - les utiliser en les convertissant en bons d'achats ou en réduction en sélectionnant les commerces liés aux partenariats.
