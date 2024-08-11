# Chapitre : CONTRAINTE DE CLE ETRANGERE


# Ajouter une contrainte de clé étrangère

Lors de la création du tableau

```
CREATE TABLE table_name (

	column1 data_type(size),
	column2 data_type(size),.....,
	column3 data_type(size),
	CONSTRAINT <constraint_name> FOREIGN KEY (column_name) REFERENCES Table_name (column_name)
);
```

# Ajouter une contrainte de clé étrangère

Après avoir créé la table

```
Alter TABLE table_name ADD CONSTRAINT <constraint_name>
FOREIGN KEY (column_name) REFERENCES Table_name (column_name);
```

Ces ressources peuvent vous aider

Utilisation des instructions DDL

[https://www.tutorialspoint.com/sql_certificate/using_ddl_statements.htm](https://www.tutorialspoint.com/sql_certificate/using_ddl_statements.htm)
