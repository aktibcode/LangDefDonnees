# Chapitre : MISE A JOUR DE LA STRUCTURE DES DONNEES

# Ajouter une colonne

Syntaxe

```
ALTER TABLE table_name ADD column1 column_type, column2 column_type;
```

Exemple

```
ALTER TABLE Student ADD Adress VARCHAR2(100);
```

Syntaxe

# Alter Column

```
ALTER TABLE table_name MODIFY column1 column_type, column2 column_type;
```

Exemple

```
ALTER TABLE Student MODIFY Adress VARCHAR2(200);
```

Syntaxe

# Drop Column

```
ALTER TABLE table_name DROP column1,column2;
```

Exemple

```
ALTER TABLE Student DROP Adress;
```

Ces ressources peuvent vous aider

Utilisation des instructions DDL

[https://www.tutorialspoint.com/sql_certificate/using_ddl_statements.htm](https://www.tutorialspoint.com/sql_certificate/using_ddl_statements.htm)
