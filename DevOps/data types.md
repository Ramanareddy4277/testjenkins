### ✅ What are Data Types in SQL?





A database is a structured collection of data that is stored electronically and can be easily accessed, managed, and updated



“A database is an organized collection of related data stored electronically that allows efficient retrieval, insertion, update, and deletion of data



Data types tell the database what type of data a column can store.



##### Example:



Numbers



Text



Dates



Boolean values



###### In MySQL, data types are divided into mainly 4 categories:



 								TINYINT



 								SMALLINT



 								MEDIUMINT



 								INT



 								BIGINT





SQL supports several categories of data types for storing different kinds of information in database columns, including strings, numbers, dates, and more. These vary slightly by database

system like MySQL, SQL Server, or Oracle, but share common patterns.

​



#### Main Categories

SQL data types generally fall into three primary groups: string (for text), numeric (for numbers), and date/time (for temporal data).

​



#### String Types

These handle characters, text, and binary data.



CHAR(size): Fixed-length string (0-255 characters).

​



VARCHAR(size): Variable-length string (up to 65,535 characters).

​



TEXT variants (TINYTEXT, TEXT, MEDIUMTEXT, LONGTEXT): For larger text storage.

​



BLOB variants (TINYBLOB, BLOB, etc.): For binary large objects like images.

​



###### Numeric Types

These store integers, decimals, and floating-point values.



INT/TINYINT/SMALLINT/MEDIUMINT/BIGINT: Integers of varying sizes (e.g., INT ranges from -2^31 to 2^31-1).

​



FLOAT/DOUBLE: Approximate floating-point numbers.

​



DECIMAL(M,D): Exact decimal values for precision (e.g., currency).

​



Date/Time Types

These manage temporal data.



DATE: Stores dates (YYYY-MM-DD).

​



DATETIME/TIMESTAMP: Date and time combinations.

​



TIME: Time only (HH:MM:SS).

​



YEAR: Year values.

​

