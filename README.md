# :weight_lifting: THE ARC DATABASE DESIGN

## :open_book: OVERVIEW
Date: October 2023\
Designer(s): Ashneet Rathore, Guillermo Bolger\
Based on assignment instructions from Prof. Mary Roth

This repository presents a relational database design for the Anteater Recreation Center (ARC), a gym located on the University of California, Irvine campus. The purpose of the database is to support core gym operations such as member management, event enrollment, employee scheduling, and facility usage. The project consists of three main artifacts: an **entity relationship diagram (ERD)**, a **relational notation** document, and a **schema** implementation with a **MySQL** script. 

The repo also includes a system requirements narrative that informed the modeling decisions and schema constraints throughout the design process. Certain requirements, such as the presence of sensor technology, were intentionally extended for design exploration purposes and do not necessarily reflect current ARC operations.

## :brain: DESIGN RATIONALE
Cardinality Constraints

Weak Entities

Attribute/Domain Constraints

Participation Constraints



## :key: ERD NOTATION KEY

| Symbol/Notation            | Meaning                                                 |
|----------------------------|---------------------------------------------------------|
| Rectangle (single border)  | Strong entity                                           |
| Rectangle (double border)  | Weak entity                                             |
| Diamond (single border)    | Regular relationship                                    | 
| Diamond (double border)    | Identifying relationship                                |
| Oval                       | Relationship attribute                                  |
| Underlined attribute       | Primary key                                             |
| Italicized attribute       | Partial key                                             |
| IS A relationship          | Inheritance relationship                                |
| Oval with "o"              | Overlapping specialization                              |
| Double line                | Total participation                                     |
| Single line                | Optional participation                                  | 
| Plain line                 | "Many" side of a 1-to-many or many-to-many relationship | 
| Line ending with arrow     | "One" side of a 1-to-1 or 1-to-many relationship        |