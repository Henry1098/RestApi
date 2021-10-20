# RestApi

API simple crée en PHP, permet la création, le delete, l'update et le listing d'un user avec Postman ou tout autre outil qui sert à exécuter des appels HTTP

Le path est:
GET

Récup. tous les users

/users/

GET

Récuperation un user

/users/{id}

POST

Creation d’un User

/users/

DELETE

Effacer User

/users/{id}

PUT

Modifier un User

/users/{id}


La table user est composé comme suit:
Id - int
name - varchar
phone - varchar
email - varchar
created - timestamp (par default date courante)
