//Progetto Next.js ristorApp con Post and Handler

//next.js, Tailwind, Zustand, server action, useForm, middleware

//MeteoApp
ReactNative

//Meals App
React-jotai-materials

//RistorApp
//.net
//MySQL
//Swagger

//banca
//.net

//elenco studenti
//react-native

//esercizio 2 
//java microservizi
//swagger
//spring-boot
//h2o db

//Battle TO Hero
//JAVA SPRING BOOT
//SQLite
//Postman

POST http://localhost:8080/rest/heroes HTTP/1.1
Content-Type: application/json

{
    "name":"Artu",
    "race":"WARRIOR",
    "health":100,
    "defence":100,
    "strenght":100,
    "level":"ADVANCED"
}
###
POST http://localhost:8080/rest/heroes HTTP/1.1
Content-Type: application/json

{
    "name":"Artu",
    "race":"MAGE",
    "health":100,
    "defence":100,
    "strenght":100,
    "level":"BEGINNER"
}
###
GET http://localhost:8080/rest/heroes HTTP/1.1

###
GET http://localhost:8080/rest/heroes/1 HTTP/1.1

###
POST http://localhost:8080/rest/battle HTTP/1.1
Content-Type: application/json

{
    "id":1,
    "id2":2
}
###
GET http://localhost:8080/rest/battle HTTP/1.1


esempi creazioni eroi e battaglie
