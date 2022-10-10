# GDA - Brief pour vendredi 30 sept
<p>Après un processus long et lent, tu es retenu en tant que développeur dans une université. Et sans attendre, il y a une mission qui t’attend et tu es très excité à l’idée de pouvoir démontrer tes compétences à tes chefs.</p>
<p>L’université souhaite optimiser sa façon de gérer les étudiants et son personnel. Ta mission consiste à mettre en place une bdd qui va faciliter la gestion de données de l’université. Afin de te faciliter la tâche, nous te proposons déjà le modèle physique que tu trouveras à la page 128 du document “Database design” disponible sur Google Classroom. Sans toi libre de le modifier si nécessaire.</p>
<p>Ce qui te reste à faire :</p>
<ul>
  <li>créer une bdd dans PostgreSQL nommée gouniv</li>
  <li>créer au moins 3 utilisateurs de la bdd ayant différents niveaux de permissions (droits):</li>
  <ul>
    <li>un admin ayant tous les droits sur toutes les tables de la bdd</li>
    <li>un 2è user qui ne peut que manipuler les tables Student et Course. Il ne peut que lire la table Staff</li>
    <li>un dernier utilisateur qui n’a que les accès en lecture seul sur les tables Student et Course</li>
  </ul>
  <li>Insérer des données (un minumum de 5 entrées)</li>
  <li>documenter ses actions (faire mention aussi des sources d'informations utilisées)</li>
</ul>
<p>Livrables : scripts sql (à exécuter sans erreurs aucune) ainsi que le document résument les différentes actions mises en place et les sources utilisées pour résoudre ce challenge</p>
