# login_jwt
es una app que usa nodejs express 
tambien se una una base de datos con MySQL 
se debe crear una schema en mi caso lo llame LOGIN 
una tabla USER : id, user, name, password
las librerias a instalar son :


express
bcryptjs
cookie-parser
dotenv
ejs
jsonwebtoken
mysql
express-session

se debe crear una carpeta dentro del proyecto llamada env
con un archivo con nombre .env con los siguientes datos: 

//definimos las variables de entorno

DB_HOST = localhost
DB_USER = root
DB_PASS = root
DB_DATABASE = login

//Definimos los datos para JWT
JWT_SECRETO = super_secret

//tiempo en el que expira el token
JWT_TIEMPO_EXPIRA = 7d
//tiempo en el que expira la cookie
JWT_COOKIE_EXPIRES = 90


https://github.com/wgekko/login_jwt/assets/62272491/15effcbc-14d9-45a2-a573-014db123f184





