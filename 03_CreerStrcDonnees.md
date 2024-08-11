# Chapitre : CREER UNE STRUCTURE DE DONNEES


# Types de données

Il existe une liste non exhaustive des types de données utilisés dans SQL. Les plus utilisés sont illustrés dans le tableau ci-dessous.

![](https://i.imgur.com/qbXIXIR.png)

# Créer un tableau

Syntaxe

```
CREATE TABLE table_name (
	column1 data_type(size),
	column2 data_type(size),
	column3 data_type(size),
	....
);
```

# Créer un tableau

Exemple

```
CREATE TABLE STUDENT (
	Student_id NUMBER(7),
	Student_name VARCHAR2(20),
	DateOfBirth DATE
);
```

DESCRIBE (ou DESC ) Étudiant ; Afin de montrer la structure du tableau

![](https://i.imgur.com/icItAcT.png)

Ces ressources peuvent vous aider

Utilisation des instructions DDL

[https://www.tutorialspoint.com/sql_certificate/using_ddl_statements.htm](https://www.tutorialspoint.com/sql_certificate/using_ddl_statements.htm)
