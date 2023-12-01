# Web Ecom App (Angular)
<hr>

Premierement nous devons creer "db.json" dans le dossier "data":

<img src="captures/dbJson.png">
<img src="captures/dbJson2.png">

<br>
Mais d'abord nous allons installer json-server avec:
<br>
"npm i json-server" et "npm i json-server-auth"

Et pour demarrer json server:
<br>
"json-server -w data/db.json -p 9000"

<br>

J'ai cree pour l'admin le JWT avec les roles: "ADMIN" et "USER":

<img src="captures/jwtAdmin.png">

<br>

Login page :

<img src="captures/adminlogin.png">

<br>

Pour l'admin: il peut consulter les produits, les modifier et les supprimer

<img src="captures/products.png">

<br>

Pour creer un produit if faut remplir et respecter le formulaire de la creation:

<img src="captures/create.png">

<br>

Un message sera affiché lors de la création du produit:

<img src="captures/newProd.png">

<br>

J'ai cree pour User le JWT avec le role: "USER"

<img src="captures/jwtUser.png">

<br>

Login page :

<img src="captures/userlogin.png">

<br>

Pour l'User: il peut seulement consulter les produits

<img src="captures/productsUser.png">

<br>

Lorsque l'utilisateur essaye de creer un produit on affiche la page de "Not Authorized" 

<img src="captures/notAuthorized.png">
