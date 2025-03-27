# Normalisation in Databases
### What is Database Normalisation?
Is the process of designing databases effectively to avoid data redundancy.

Data redundancy simply is data duplication. We can have values of certain columns repeated multiple times.

### Different Levels of Normalisations
### 1. 1NF - FIRST NORMAL FORM
### Rules for 1NF
- Every column can only have a single value
- Each row should be unique, either through a single or multiple columns

### 2. 2NF - SECOND NORMAL FORM
### Rules for 2NF
- Must be in 1NF
- All non key attributes must be fully dependent on candidate key i.e If a non-key column is partially dependent on candidate key (subset of columns forming candidate key) then split them into separate tables.
- Every table should have primary key and relationship between the tables should be formed using foreign key.

### 3. 3NF - THIRD NORMAL FORM
### Rules for 3NF
- Must be in 2NF
- Avoid Transitive dependencies(i.e if A is dependent on B and B is dependent on C then A is dependent on C).