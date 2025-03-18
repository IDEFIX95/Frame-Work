# Frame-Work
Projet Frame-Work Ing1 Dev-Web 2nd Semestre

3 exemples sont disponibles : du plus simple à mettre en place aux plus compliqués.

Dans un 1er temps, avant même de tester les exemples, il faut absolument lancer le fichier "DemoApplication.java", qui est considéré comme le cerveau.

Il importe les bibliothèques et le contenu qui vont permettre de lancer le framework Spring. Sans lui, on ne peut pas utiliser Spring.

Ensuite, une fois ce fichier lancé, on peut se rendre sur un navigateur internet et taper dans la barre de recherche "http://localhost:8080/...".

C'est à partir de ce port HTTP que l'on va pouvoir tester nos exemples.

** Pour le 1er exemple, vous pouvez taper dans la barre de recherche l'adresse suivante : "http://localhost:8080/" puis "http://localhost:8080/bonjour/hello".

Je vous laisse découvrir ce que cela fait apparaître à l'écran.

** Pour le 2ᵉ exemple, vous pouvez taper ceci : "http://localhost:8080/api/manipulate?prenom=Votre_Prenom".

À la place de "Votre_Prenom", mettez le vôtre pour voir ce que cela donne.

** Pour le dernier exemple, c'est quelque chose d'un peu plus développé. Mais l'idée, c'est d'envoyer ce qui est mis dans un formulaire d'inscription vers un fichier JSON.

Il faut lancer, dans un 1er temps, le fichier HTML nommé "index.html", qui se situe ici : "demo\src\main\resources\templates".

Une fois fait, tu peux aussi te rendre sur cette adresse : "http://localhost:8080/users" pour observer que les données sont bien transmises vers le JSON.

On peut aussi supprimer depuis le fichier HTML.

Dernière petite chose : si on veut voir quelle adresse on doit mettre pour avoir tel exemple, il faut se rendre dans le dossier "controller".

Dans ce dossier, si tu cliques sur un fichier, regarde la ligne avec "@GetMapping(“....”)". Tu auras juste à prendre le lien et le mettre dans le navigateur.
