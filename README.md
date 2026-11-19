# Limova Desktop — releases

Ce dépôt ne contient **aucun code source**. Il sert uniquement à distribuer Limova Desktop :

- les installeurs signés et notarisés (`.dmg` pour macOS) ;
- le fichier `latest.json` que l'application lit pour se mettre à jour toute seule.

Les releases sont publiées par la CI du dépôt privé `Limova-2-0/team-desktop`. Elles arrivent
en brouillon : une personne de l'équipe les relit puis les publie. Tant qu'une release est en
brouillon, aucune application installée ne la voit.

Il est public parce que l'application télécharge ses mises à jour sans authentification. Chaque
mise à jour est signée : une application installée refuse tout fichier qui ne porte pas la
signature de Limova.
