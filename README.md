# Normal-Forms-Problem-Set
A project to identify violations in first, second or third normal form and explain its causes for an Events Dataset.


Normal forms are a set of principles used to minimize data redundancy and improve the structure of relational databases. A dataset can comply with a normal form by adhering to the criteria set forth by that form. <br>

First Normal Form (1NF):<br>
•	The data is stored in a relation format. <br>
•	There are no repeating groups of data. <br>
•	All attributes are atomic (single value). <br>
•	There is a primary key.<br>

Violation criteria:<br>
•	Data is not stored in a relation format. <br>
•	There are repeating groups of data. <br>
•	Attributes are not atomic (multiple values). <br>
•	There is no primary key. <br>

Second Normal Form (2NF): <br>
•	It must meet all the criteria of the First Normal Form. <br>
•	It should not have any partial dependencies. <br>
•	Each non-key attribute must depend on the entire primary key.<br>

Violation criteria: <br>
•	It does not meet all the criteria of the First Normal Form. <br>
•	It has partial dependencies. <br>
•	Non-key attributes do not depend on the entire primary key. <br>

Third Normal Form (3NF): <br>
•	It must meet all the criteria of the Second Normal Form.<br> 
•	It should not have any transitive dependencies. <br>
•	Non-key attributes should not depend on other non-key attributes.<br>

Violation criteria: <br>
•	It does not meet all the criteria of the Second Normal Form. <br>
•	It has transitive dependencies. <br>
•	Non-key attributes depend on other non-key attributes.<br>
