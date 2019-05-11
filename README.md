# Spring_JDBC

Démarrer une API pour récupérer des informations sur les écoles de magie :

  - Génère un projet Spring, dans lequel tu vas créer un contrôleur.
  - Retourne pour la route /api/schools -- méthode GET -- toutes les écoles de la table school. Retourne bien tous les champs de la table : id, name, capacity, country.
  - Si la route contient un paramètre country, retourne uniquement les écoles du pays demandé. Par exemple, pour /api/schools?country=France, tu dois retourner uniquement les écoles françaises.
  - Pousse le contenu de ton projet dans un dépôt GitHub et poste le lien de ton dépôt en guise de solution.
  
  # Critères de validation
  
    - Le projet contient un contrôleur séparé de l'application.
    - La route /api/schools retourne tous les champs pour toutes les écoles de la table school.
    - Les résultats peuvent être filtrés par un paramètre country.
    - Le code est disponible sur GitHub.

  # Correction
  
    J'ai rajouté un dossier "postman" à la racine du projet pour visualiser:
  
      - une requete qui retourne toutes les écoles de la table school: http://localhost:8080/api/schools 
      - une requete qui retourne les écoles du pays demandé: http://localhost:8080/api/schools?pays=France
      
