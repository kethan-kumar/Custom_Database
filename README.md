Database & its management system (DBMS)

The database and its management system would simulate a basic system like MySQL and implements multiple database
queries.

Functionalities:
- Basic Menu with multiple options like
  1. New user
  2. Existing user
  3. MySQL Command prompt
  4. MySQL Dump
  5. Export ERD
  6. Exit from application 
 
SQL queries functional in the current version:
- Regular expression for the queries have been implemented without any library support.
  . CREATE
  . INSERT
  . UPDATE
  . DELETE
  . SELECT
  . SQL DUMP
  . ERD generation
  . FOREIGN KEY support

User store instructions:

- user_store.enc_copy: it's an empty user store with the columns [username, password]

- take the copy of 'user_store.enc_copy' from main_module and rename it to 'user_store.enc'.

- Place 'user_store.enc' parallel to AuthenticationMechanism.py for the program to use.

- Refer PNGs for sample execution
