# Documentation des classes de l'application nodejs gsb1
--
## HomeController

### constructor
    fait appel au constructor de la classe mere
### index
    methode qui rend la vue index
### User
    methode qui rend la vue user
### Dashboard
    methode qui rend la vue dashboard pour l'admin
    
## AuthController
--
### Constructor
    fait appel au constructor de la classe mere
### Signup
    methode qui réalise le traitement d'inscription d'un user dans la base de donnée
### Login
    Methode qui prend en parametre le passport pour gerer les séssions et qui connecte un utilisateur
### Logout
    Metthode qui deconnecte un user
--
## ApiController

### Constructor
    fait appel au constructor de la classe mere
### Foods
    Methode qui utilise le model foods et qui renvoi du JSON
### FoodGroups
    Methode qui utilise le model foodGroup et qui renvoi du JSON
### UpdateUserFoods
    Methode qui actualise la liste des aliments ingérer par un user
### UserFoods
    Methode qui utilise le model User et qui renvoi en JSON la liste des aliments ingérer par ce user
### NewFood
    Methode qui permet d'ajouter un aliments a la base de donnée par l'admin
--
## Controller

### Data
    Methode qui permet de partager l'objet Data avec toutes les classes dérivées
--

## Users

### Constructor
    Prend en parametre l'objet mongoose pour gerer la connection a la base de donnée
    this.schema defini le schema du model
    this.model defini le model mongoose associé
### get Schema
    Permet d'acceder a this.schema
### get Model
    Permet d'acceder a this.model
--

## Foods

### Constructor
    Prend en parametre l'objet mongoose pour gerer la connection a la base de donnée
    this.schema defini le schema du model
    this.model defini le model mongoose associé
### get Schema
    Permet d'acceder a this.schema
### get Model
    Permet d'acceder a this.model
--

## FoodGroups

### Constructor
    Prend en parametre l'objet mongoose pour gerer la connection a la base de donnée
    this.schema defini le schema du model
    this.model defini le model mongoose associé
### get Schema
    Permet d'acceder a this.schema
### get Model
    Permet d'acceder a this.model
--

