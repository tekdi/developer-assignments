> Bad programmers worry about the code. Good programmers worry about data structures and their relationships.
_Linus Torvalds_
 	
Relational data is one of the pillars of applications. Picking the right data structure and relationships during application design is a skill, or rather an art that is important to acquire. This challenge will help you demonstrate the same.

# Problem Statement
1. Build a MySQL database schema for an e-commerce site products master. The master table(s) should fulfil the following criteria
- Each product has a name and unique id
- Each product can have multiple prices, depending on the quantity being bought
- The database will have lacs of records, so give a due consideration to performance

Some sample data for you to use

| Product | Quantity Bought | Unit Price |
| ------  | ----------      | ----- |
| Earphones | 1 to 10 | 500 |
|  | 11 to 50 | 485 |
|  | 51 to 200 | 475 |
|  | 201 to 1000 | 450 |
| Memory Card | 1 to 50 | 1000 |
|  | 51 to 200 | 950 |
|  | 201 to 1000 | 900 |
| Hammer | 1 to 5 | 250 |
|  | 6 to 50 | 240 |
|  | 51 to 200 | 230 |
|  | 201 to 1000 | 220 |

2. Write SQL queries to get the following information
- Name of the most expensive product(s)
- Name of the cheapest product(s)
- Per item price for 75 memory cards
- Per item price for 6 hammers

# Solutions
Email us 2 text files. First text file that has the create statements for the table(s). The second text file should have the SQL queries.
