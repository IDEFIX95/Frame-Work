# Frame-Work
Projet Frame-Work Ing1 Dev-Web 2nd Semestre

3 Exemples sont disponibles : Dû plus simple à mettre en place aux plus compliqués

Dans un 1er temps avant même de tester les exemples il faut absolument lancer le fichier " DemoApplication.java" qui est considéré comme le cerveau.

Il importe les bibliotheques et le contenu qui va permettre de lancer le framework Spring. Sans lui on ne peut pas utiliser Spring.

Ensuite une fois ce fichier lancé on peut se rendre sur un navigateur internet et taper dans la barre de recherche " http://localhost:8080/... ".

C'est à partir de ce port http que l'on va pouvoir tester nos exemples.

** Dans un premier temps vous pouvez taper dans la barre de recherche l'adresse suivant : " http://localhost:8080/ " et ensuite " http://localhost:8080/bonjour/hello ". 

Je vous laisse découvrir ce que cela fait apparaitre à l'écran.

** Pour le 2eme exemple vous pouvez taper ceci " http://localhost:8080/api/manipulate?prenom=Votre_Prenom " . 

A la place de " Votre_Prenom " mettez le votre pour voir ce que cela donne.

** Pour le dernier exemple c'est quelque chose d'un peu plus developpé. 
Mais l'idée c'est d'envoyé ce qui est mis dans un formulaire d'inscription vers un fichier Json.

Il faut lancer dans un 1er temps le fichier html nommé " index.html " qui ce situe ici " demo\src\main\resources\templates "

Une fois fait tu peux aussi te rendre sur cette adresse " http://localhost:8080/users " pour observer que les données sont bien transmise vers le Json.

On peut aussi supprimer depuis le fichier html.

Derniere petite chose si on veut voir quelle adresse on doit mettre pour avoir tels exemples. Il faut ce rendre dans le dossier " controller ".

Dans ce dossier si tu cliques sur un fchier regarde la ligne avec marqué " @GetMapping("....") ". Tu auras juste à prendre le lien et le mettre dans le navigateur.
