# Instances_UPMSP_RD
Ce repository contient un script Python pour sélectionner des instances représentatives à partir d'un ensemble de données d'instances du problème d'ordonnancement à machines parallèles. L'objectif est de sélectionner un petit ensemble d'instances qui sont représentatives de l'ensemble complet pour tester une nouvelle méthode de résolution du problème.

Le script utilise l'algorithme de clustering k-means pour regrouper les instances en clusters. Ensuite, pour chaque cluster, il sélectionne l'instance la plus proche du centroïde comme représentant. Les instances représentatives sélectionnées peuvent ensuite être utilisées pour tester la nouvelle méthode de résolution du problème.

Le script utilise la bibliothèque scikit-learn pour implémenter l'algorithme de clustering k-means. Les données sont lues à partir d'un fichier CSV et les caractéristiques pertinentes sont spécifiées dans le script. Le nombre de clusters est également spécifié dans le script.

Le script produit un nouveau fichier CSV contenant les instances représentatives sélectionnées, ainsi que les identifiants et les résultats obtenus pour ces instances.
