# API-RESTful
Créer une API RESTful permettant aux utilisateurs de gérer une liste de tâches. Cela nous permet de :

Créer une nouvelle tâche (POST /tasks)

Lire la liste des tâches (GET /tasks)

Afficher une tâche spécifique (GET /tasks/:id)

Modifier une tâche (PUT /tasks/:id)

Supprimer une tâche (DELETE /tasks/:id)

# Comment ça fonctionne?
 D'abord ,il faut installer express,postman et en suite créer le serveur.

 Après écrire le code permetant à l'utilisateur de créer,lire ,afficher ,modifiier et supprimer une tâche.Une fois que le code a été écrit,on utilse le code suivant pour lancer le serveur : node serveur.js. si le serveur marche vous verrai " Serveur démarré sur http://localhost:4000 " et avec ce lien http vous allez pouvoir verifier si le serveur marche,si ça marche vous allez voir un message apparaître comme ceci :  
 
 { "message": "Bienvenue sur API-Tanguy!" }.

# comment l'utilisateur de créer,lire ,afficher ,modifiier et supprimer une tâche?

 Une fois que tout est en place vous pouvez :

Créer une nouvelle tâche (POST /tasks).

une fois dans postman suivez les étapes suivantes:

 1- choisir POST : entrer le lien http://localhost:4000/tasks
 -choisir body ,raw,JSON
 - ajouter la tachê que vous voulez comme suit :
 {
    "title": "nom de la tachê"
 }
 - si vous voulez ajouter une autre tachê ,faite la même chose juste en changeant le title.
 - choisir GET  : entrer le lien http://localhost:4000/tasks pour recuperer les tâches créer au préalable.
 - choisir GET  : entrer le lien http://localhost:4000/tasks/id pour recuperer une tâche créer au préalable.
 - choisir PUT : entrer le lien http://localhost:4000/tasks/id pour modifier une tâche créer au préalable.
 - choisir DELETE : entrer le lien http://localhost:4000/tasks/id pour pour supprimer une tâche créer au préalable.

