# Chapitre : CONTRAINTE DE CLE PRIMAIRE


# Ajouter une contrainte de clé primaire simple

* Niveau colonne : lors de la création du tableau

```
CREATE TABLE table_name (
	column1 data_type(size) CONSTRAINT <constraint_name> PRIMARY KEY,
	column2 data_type(size),.....,
	column3 data_type(size)
);
```

* Niveau de la table

```
Alter Table table_name ADD CONSTRAINT <constraint_name> PRIMARY KEY(column_name);
```

# Ajouter une contrainte de clé primaire simple

Exemple

```
Alter Table Student ADD CONSTRAINT pk_student PRIMARY KEY(student_id);
```

![](https://i.imgur.com/9WF5Rxa.png)

# Ajouter une contrainte de clé primaire composée

* Solution 1 : lors de la création du tableau

```
CREATE TABLE table_name (
	column1 data_type(size),
	column2 data_type(size),.....,
	column3 data_type(size),
	CONSTRAINT <constraint_name> PRIMARY KEY (column1,column2)
);
```

* Solution 2:

```
Alter Table table_name ADD CONSTRAINT <constraint_name> PRIMARY KEY(column1,column2);
```

# Supprimer une contrainte de clé primaire

* Syntaxe:

```
Drop CONSTRAINT constraint_name;
```

Ces ressources peuvent vous aider

Utilisation des instructions DDL

[https://www.tutorialspoint.com/sql_certificate/using_ddl_statements.htm](https://www.tutorialspoint.com/sql_certificate/using_ddl_statements.htm)
