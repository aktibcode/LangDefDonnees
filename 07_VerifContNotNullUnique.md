# Chapitre : NotNull, Unique,  VERIFIER LES CONTRAINTES


# Ajouter une contrainte Not Null

Lors de la création du tableau

```
CREATE TABLE table_name(

	column1 data_type(size) CONSTRAINT <constraint_name> NOT NULL ,
	,...,
);
```

Après avoir créé la table

```
ALTER TABLE table_name modify column_name data_type CONSTRAINT <constraint_name> NOT NULL;
```

La contrainte **NOT NULL** doit être définie uniquement au **niveau de la colonne** .

# Ajouter une contrainte unique

Lors de la création du tableau

```
CREATE TABLE table_name (

	column1 data_type CONSTRAINT <constraint_name> UNIQUE ,
	,...,
);
```

Après avoir créé la table

```
ALTER TABLE table_name ADD CONSTRAINT <constraint_name> UNIQUE (column_name);
```

Une contrainte **UNIQUE** autorise les valeurs **NULL** sauf si vous définissez des contraintes **NOT NULL**

# Ajouter une contrainte de vérification

La contrainte **CHECK** garantit que toutes les valeurs d'une colonne satisfont **certaines conditions** .
Lors de la création de la table

```
CREATE TABLE table_name(

	column1 data_type CONSTRAINT <constraint_name> CHECK (condition) ,
	,...,
);
```

Après avoir créé la table

```
ALTER TABLE table_name ADD CONSTRAINT <constraint_name> CHECK (condition);
```

Ces ressources peuvent vous aider

Utilisation des instructions DDL

[https://www.tutorialspoint.com/sql_certificate/using_ddl_statements.htm](https://www.tutorialspoint.com/sql_certificate/using_ddl_statements.htm)
