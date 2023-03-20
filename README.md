

OUNES CART

RAPPORT

PROJET

Préparé par :

Younes SHIMI

Approuvé par :

MERYEM HNIDA





**Remerciements**

Je tiens à exprimer mes sincères remerciements à ma professeur

pour son aide précieuse et son soutien constant tout au long de la

réalisation de mon projet. Sa disponibilité, ses conseils et sa

guidance ont été déterminants pour la réussite de mon travail. Je

lui suis profondément reconnaissant.

**Introduction**

" Je suis ravi de vous présenter mon projet de création d'un site e-

commerce appelé Ounes-cart.

Ce projet a pour objectif de proposer une plateforme en ligne pour

l'achat de produits de qualité à des prix compétitifs.

Les utilisateurs pourront naviguer facilement sur le site pour

trouver les produits qu'ils cherchent, grâce à une interface intuitive

et une catégorisation claire des produits. Le site proposera

également des options de paiement sécurisées pour garantir la

sécurité des transactions. Notre engagement est de fournir un

service clientèle de qualité pour répondre à toutes les questions et

préoccupations des utilisateurs. Nous allons continuer à améliorer

le site pour répondre aux besoins et aux attentes des utilisateurs.

Je suis enthousiaste à l'idée de lancer ce projet et j'espère que

vous apprécierez votre expérience d'achat sur Ounes-cart. "





**Besoins fonctionnels**

Les besoins fonctionnels de mon site e-commerce Ounes-cart se

basent sur la méthode CRUD (Create, Read, Update, Delete). Cela

signifie que les utilisateurs peuvent effectuer les actions suivantes

sur le site :

Créer un compte utilisateur pour accéder à des fonctionnalités

supplémentaires

Rechercher et consulter les produits disponibles sur le site

Mettre à jour les informations de leur compte utilisateur, comme

l'adresse de livraison ou les détails de paiement

Supprimer des articles de leur panier ou annuler une commande

en cours

Ces fonctionnalités CRUD de base sont essentielles pour une

plateforme e-commerce efficace et conviviale. Elles permettent aux

utilisateurs de facilement naviguer, sélectionner et acheter des

produits, ainsi que de gérer leur compte utilisateur en toute

sécurité.





**G[énéralisation**](https://www.cairn.info/revue-empan-2002-1-page-19.htm)**

Mon projet de site e-commerce Ounes-cart est un projet qui a été

donné à réaliser dans le cadre de mes études en première année de

cycle ingénieur, semestre 7. Il a pour but de mettre en pratique les

connaissances acquises en développement web et en utilisant le

module Node.js.

Le site Ounes-cart est une plateforme en ligne qui permet aux

utilisateurs de parcourir et d'acheter des produits en ligne. Il offre

une interface utilisateur intuitive avec des fonctionnalités telles

que la recherche de produits, l'ajout de produits au panier, la

gestion de compte utilisateur et le paiement en ligne sécurisé.

Le projet est développé en utilisant le module Node.js pour la

gestion du backend, avec un utilisation de Express.js framework

pour gérer les routes et les requêtes HTTP. Le côté frontend est

gérer en utilisant des technologies telles que HTML, CSS et

JavaScript pour créer une interface utilisateur conviviale et

réactive. La base de données est gérée en utilisant MongoDB pour

stocker les informations des utilisateurs et les détails des

produits.

En résumé, mon projet de site e-commerce Ounes-cart est un projet

qui utilise Node.js, Express.js, HTML, CSS, JavaScript et MongoDB

pour créer une plateforme e-commerce complète et fonctionnelle. Il

a été conçu pour mettre en pratique les connaissances acquises en

développement web et pour fournir une expérience utilisateur

agréable.





Langages utilisées :

Dans mon projet de site e-commerce Ounes-cart, j'ai utilisé plusieurs

langages de programmation pour créer une plateforme complète et

fonctionnelle. Les principaux langages utilisés sont :

EJS (Embedded JavaScript) : Il est utilisé pour créer des modèles

pour les pages web. Il permet de combiner du code JavaScript et HTML

pour générer des pages dynamiques.

HTML : Il est utilisé pour structurer le contenu de chaque page web.

Il permet de définir les titres, les paragraphes, les images, les liens,

etc.

CSS : Il est utilisé pour définir les styles pour chaque page web. Il

permet de changer la couleur, la police, la mise en page, etc.

Bootstrap : Il est utilisé pour créer une interface utilisateur

responsive et moderne. Il fournit des classes et des composants

prédéfinis pour faciliter la création de pages web.

Node.js : Il est utilisé pour gérer le backend de l'application. Il

permet de gérer les routes, les requêtes HTTP, les sessions, etc.

JavaScript : Il est utilisé pour ajouter des fonctionnalités

interactives aux pages web. Il permet de valider les formulaires, de

gérer les animations, de gérer les interactions utilisateur, etc.

Ces différents langages sont utilisés ensemble pour créer une

plateforme e-commerce complète et fonctionnelle, avec une interface

utilisateur moderne et réactive, une gestion de compte utilisateur

sécurisée et des fonctionnalités de paiement en ligne.





Mise en place de l'application Web

"Ounes-Cart"





**Conception**

Introduction

Après avoir cité les différentes fonctionnalités de notre projet dans le

deuxième chapitre. on va commencer maintenant une phase importante et

indispensable dans le cycle de vie d'une application.

cette phase est la conception qui a pour but d'expliquer le déroulement de

mon application ainsi qu'assurer une bonne compréhension de besoins

utilisateurs.

Méthodologie et approche adoptée

Pour la conception de notre systéme nous avons adopté une méthode

objet, en effet l'approche objet est une approche incontournable dans le

cadre de dévloppement des qpplication.

Pour mieux présenter l'architecture de notre application, on va choisir le

langage de modélisation le plus adopté UML (Unified Modeling Langage)

car il présente plusieurs avantages :

1\. il facile la compréhension de représentations abstraites complexes

2\. Son caractère polyvalent et sa souplesse en font un language universel

3\. il cadre l'analyse





La démarche de conception

les acteurs :

La modélisation des acteurs avec UML (Unified Modeling Language) est un

moyen de représenter graphiquement les différents acteurs qui

interagissent avec un système. Pour mon projet de site e-commerce Ounes-

cart, j'ai identifié deux acteurs principaux :

1\.Utilisateur normal : Il s'agit de l'utilisateur qui visite le site pour

acheter des produits. Il peut naviguer sur le site, consulter les produits,

les ajouter au panier, passer commande, et payer en ligne. Il peut

également créer un compte pour enregistrer ses informations et suivre

l'historique de ses commandes.

2\.Administrateur : Il s'agit de l'utilisateur qui gère le site e-commerce. Il

peut ajouter des produits, les supprimer, les mettre à jour, et gérer les

commandes. Il peut également gérer les utilisateurs, les informations

de paiement et les informations de livraison.

Diagramme

de cas d'utilisation





Fichier de démarrage de serveur

Il s'agit d'un code écrit en JavaScript à l'aide du framework Express.

Il s'agit d'une application Web qui se connecte à une base de données MongoDB à l'aide de la bibliothèque

Mongoose.

Il utilise divers modules tels que Multer, Passport et Method-Override pour gérer les téléchargements de

fichiers,

l'authentification et les soumissions de formulaire respectivement.

L'application utilise plusieurs routes pour gérer différents types de demandes telles que les routes de produits,

routes d'authentification, routes utilisateur, routes de commande et routes d'administration.

La stratégie Google OAuth 2.0 est utilisée pour l'authentification des utilisateurs et le code utilise

Fichier .env pour le stockage des variables env.

L'application possède également d'autres fonctionnalités telles que les messages flash et la gestion de session.

Dans l'ensemble, il semble s'agir d'une application Web de commerce électronique

avec diverses fonctionnalités pour les produits, les utilisateurs et les commandes.

app.listen(process.env.PORT || 3000, () => {

console.log(`Server started at port ${process.env.PORT || 3000}`);

});

C'est une autre façon de lancer le serveur en utilisant la fonction "app.listen()" de Express.

Il utilise la variable d'environnement "process.env.PORT" pour définir le port sur lequel le

serveur doit écouter. Si cette variable n'est pas définie, le serveur écoutera sur le port 3000

par défaut. Cela permet de faciliter le déploiement du serveur sur un serveur distant ou sur

un service d'hébergement en utilisant un port défini par l'environnement plutôt que de

spécifier un port fixe dans le code.





Connection avec MongoDB

mongoose

.connect(process.env.MDB\_CONNECT, {

useNewUrlParser: true,

useUnifiedTopology: true,

useFindAndModify: false,

useCreateIndex: true,

})

.then(() => {

console.log("Database is connected");

})

.catch((err) => {

console.log("Data Base Error...");

console.log(err);

});

Ceci est une partie de code qui utilise Mongoose, un module Node.js qui facilite

l'interaction avec une base de données MongoDB. Il utilise la méthode "connect()" pour

établir une connexion à la base de données en utilisant une URL de connexion stockée dans

la variable d'environnement "process.env.MDB\_CONNECT".

Il utilise également différentes options pour améliorer les performances et la sécurité de la

connexion, comme "useNewUrlParser" qui utilise un parseur d'URL plus récent,

"useUnifiedTopology" qui utilise une topologie unifiée pour la connexion à la base de

données, "useFindAndModify" et "useCreateIndex" qui améliorent les performances des

requêtes de modification et de recherche.

Il y a un callback then qui est executer en cas de connexion reussi avec la base de données

et un catch qui est executer en cas d'erreur.

Il est important de noter que pour utiliser cette fonctionnalité, vous devez disposer d'une

base de données MongoDB en cours d'exécution et de l'URL de connexion appropriée

stockée dans la variable d'environnement "process.env.MDB\_CONNECT".





Ce morceau de code est un fichier de démarrage de serveur Node.js pour

Ounes Cart. Il importe différentes dépendances, telles que Express,

Mongoose, Multer, Passport, etc. Il configure également la connexion à la

base de données MongoDB, l'utilisation des sessions, des stratégies

d'authentification, etc. Il utilise également des routes pour différentes

sections du site, comme les produits, l'authentification, les utilisateurs, les

commandes, l'administration, etc. Il définit également un port pour lancer le

serveur et écoute les demandes de connexion.





**Réalisation**

figure : page d'accueil

figure : page d'iinscription





figure : page de connexion

figure : page D'admin





figure : page gérer Produit

figure : page gérer user





**VOUS TROUVEREZ CI**

**JOINT LA VIDEO DE**

**SIMULATION\***

**OUNES-CART**

[**H**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[T**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[T**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[P**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[S**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[:**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[/**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[/**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[W**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[W**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[W**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[.**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[M**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[E**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[D**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[I**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[A**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[F**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[I**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[R**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[E**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[.**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[C**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[O**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[M**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[/**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[F**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[I**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[L**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[E**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[/**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[W**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[2**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[G**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[K**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[8**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[9**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[S**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[X**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[Q**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)

[**A**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[U**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[X**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[8**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[Q**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[4**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[/**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[O**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[U**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[N**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[E**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[S**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[-**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[C**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[A**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[R**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[T**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[.**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[M**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[P**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[4**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[/**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[F**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[I**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[L**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[** ](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)[E**](https://www.mediafire.com/file/s9f80t3jg26fu7s/Final+Part+1+Vitess.mp4/file)

Younes Shimi

EIDIA spécialité technologie de

web et mobile

MODULE : NODEJS

