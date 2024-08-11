# Chapitre : INTRODUCTION A SQL


# Définition SQL

![](https://i.imgur.com/AG0Pxi0.png)

* Le modèle physique de données consiste à mettre en place une base de données dans un SGBDR.
* Le langage utilisé pour ce type d'opération est **SQL (Structured Query Language)** .
* SQL est composé de :
  * Langage de définition de données (DDL)
  * Langage de manipulation de données (DML)
  * Langage de requête de données (DQL)
  * Langage de contrôle des données (DCL)

# Définition SQL

SQL est le langage standard des SGBDR qui fournit un ensemble de fonctionnalités pour les requêtes, la création de structures de données, la manipulation et le contrôle des données.

```
CREATE TABLE Customer (
	customerID NUMBER CHECK (customerID > 0) PRIMARY KEY,
	name VARCHAR(30) NOT NULL,
	street VARCHAR(30) NOT NULL,
	postcode NUMBER CHECK (postcode > 0),
	city VARCHAR(20)
);
```

Ces ressources peuvent vous aider

Qu'est-ce que SQL et comment est-il utilisé ?

[https://www.thebalancecareers.com/what-is-sql-and-uses-2071909](https://www.thebalancecareers.com/what-is-sql-and-uses-2071909)
