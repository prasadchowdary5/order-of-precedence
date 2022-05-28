The Order of Precedence used by Excel to calculate formulas is extremely important to know when building complex formulas.

Of course, Excel will respect all mathematical rules you learned in school, there are only a few more Operators in Excel: the Range Operators, single Space Operator, Union Operator, the Concatenation Operator and the Exponentiation Operator.


The following table is a complete list of the Order of Precedence used by Excel:

Operator	Description	Order of Precedence
: (colon)
(single space)

, (comma)

Range operator
Intersection operator

Union operator

1st
–	Negation operator (as in –1)	2nd
%	Percent operator	3rd
^	Exponentiation operator	4th
* and /	Multiplication and division operators	5th
+ and –	Addition and subtraction operators	6th
&	Connects two strings of text (concatenation)	7th
=, <, >, <=, >=, <>	Comparison operators	8th
If your formula contains operators with the same Precedence Operator — for example, if a formula contains the GTE operator (Greater Than or Equal To: “>=” ) and the LTE operator (Lower Than or Equal To: “<=” ) , Excel will evaluate the operators from left to right.

Just to give you a small example, =10/2/5 will give you the same result as: =10/(2*5), because in the first example, we have 2 Division Operators, and in this case Excel will evaluate the formula from left to right: =10/2/5=5/5 = 1. In the second version, excel will calculate the parantheses first: =10/(2*5)=10/10=1. Notice that Excel will respect the Order of Precedence inside parantheses too, in this example: =(2*3+20), 2*3 will be calculated first, then 20 will be added to the result.
