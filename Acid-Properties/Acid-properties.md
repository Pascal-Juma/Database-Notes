# ACID Properties in DataBases Management Systems
### Transaction - A logical unit of work on a database.
### An action or series of actions that are being performed by a single user or application program, which reads or updates the contents of the database.

## A - Atomicity
-  The entire transaction takes place at once or doesn't happen at all, i.e when sending money from one account to another either the process is completed or nothing happened.

## C - Consistency
- Consistency means correctness i.e data integrity constraints must be maintained.
- For instance, after a successful money transfer we expect that both accounts will have balances that reflect the operations made on them. 

## I - Isolation 
- Multiple transation can occur concurrently without leading to the inconsistency of database state.
- For example, if two users are tansacting money concurrently from let say a banking system, the end  result of their accounts should reflect their individual operations without being affected by the other user.

## D - Durability 
- Once a transaction is committed, the updates and manipulation to the database are stored permanently even if the system failure occurs.
- For instance, if a user has successfully transferred money from one account to another, the transaction is stored permanently in the database even if the system crashes or fails.