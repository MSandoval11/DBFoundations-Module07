# DBFoundations-Module07

Madeline Sandoval

August 22, 2022

IT FDN 130A

Assignment 7

https://github.com/MSandoval11/DBFoundations-Module07

## **Functions**

**Introduction**
Functions encapsulate a SQL query so that it does not need to be written each time. They can be used to retrieve specific data and perform calculations, among other tasks.

**SQL User Defined Functions**
In SQL, a function is a named collection of code. There can be built-in functions in a RDMS or users can create custom functions, which are called user defined functions (UDFs). There are two broad categories of functions: functions that return one value and functions that return a table. A function that returns one value is a scalar function. This type of function can be used for Check constraints. A user defined function is useful because it can be created, stored in the database and called again over time.

**Scalar, Inline, and Multi-Statement Functions**
Scalar functions return a single value. For example, a scalar function can be used to return the value of a complex calculation. The function can be used instead of the longer code whenever the calculation is needed. Scalar functions can include a parameter that is set to return specific information. Inline and multi-statement functions can also use parameters. Inline functions use only one SELECT statement. The columns contained in the SELECT statement, define the columns that are returned when the function is called. A multi-statement function is similar to the in-line function but it involves additional processing. A multi-state function involves declaring the return table structure, utilizing a table variable. A statement, such as a SELECT statement, is used to choose data to be represented in the final table produced by the function. Functions have certain limitations. They cannot modify permanent data tables. A function cannot utilize a normal stored procedure. Additionally, non-deterministic system functions cannot  be used by functions. Functions also have limitations on their ability to discover errors. TRY and CATCH cannot be used with a function. 

**Conclusion**
Functions are useful tools to select specific information from a database. Depending on the type of function, they can return information as a single value or a table. 

**Citations**
1. “Functions-02 User Defined Functions UDFs”. Randal Root. https://www.youtube.com/watch?v=XEiQ3M2LhU4&list=PLfycUyp06LG9wAGPKBZ7poK
BcbDZrmXpi&index=2. (Links to external site)
2. “Inline and multi-statement table-valued functions”. Wise Owl Training. https://www.wiseowl.co.uk/blog/s347/multi-statement.htm (Links to external site)
3. “SQL Server Programming Part 10 - Table Valued Functions” Wise Owl Tutorials. https://www.youtube.com/watch?v=nCAEgNxC7nU&list=PLfycUyp06LG9wAGPKBZ7poKBcbDZrmXpi&index=5. (Links to external site)
