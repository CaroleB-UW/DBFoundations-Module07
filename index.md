
###### Author: Carole Bianquis
###### Class:Foundation of DataBases
###### Date: 12/02/2020
###### https://github.com/CaroleB-UW/DBFoundations-Module07/


#### Introduction
This paper introduces different types of SQL functions.

#### 1.	Explain when you would use a SQL UDF.
I would use a SQL UDF (User-Defined Function) when there is no built-in functions available to perform the operations I need. One example is if need to be able to enter parameters in the program. The Function will return results depending on the value of the parameters. 

#### 2. Explain are the differences between Scalar, Inline, and Multi-Statement Functions.
- Scalar Function: The scalar function returns a single value. 
-	Inline Function: An inline function is similar to a view. It contains a single select statement. In this case, since we are trying to keep our code as simple as possible, a view might be a better solution.
-	Multi-Statement Function: a multi-statement function allows to execute multiple queries and aggregate the results in one return table. 

#### Summary
There are different types of functions available for different interaction needs with the database. 
