# Boolean Truth Tables

|Not(!)|true?|
|------|------|
|!false|true|
|!true|false|

|OR(\|\|)|true?|
|------|------|
|true\|\|false|true|
|true\|\|true|true|
|false\|\|true|true|
|false\|\|false|false|

|AND(&&)|true?|
|------|------|
|true&&false|false|
|true&&true|true|
|false&&true|false|
|false&&false|false|

|NOT OR|true?|
|------|------|
|!(true\|\|false)|false
|!(true\|\|true)|false|
|!(false\|\|true)|false|
|!(false\|\|false)|true|

|NOT AND|true?|
|------|------|
|!(true&&false|true|
|!(true&&true)|false|
|!(false&&true)|true|
|!(false&&false)|true|

|NOT EQUAL(!=)|true?|
|------|------|
|1 != 0|true|
|1 != 1|false|
|0 != 1|true|
|0 != 0|false|

|EQUAL(==)|true?|
|------|------|
|1 == 0|false|
|1 == 1|true|
|0 == 1|false|
|0 == 0|true|

# Arithmetic Operators

|Operator|Description|Example|
|------|------------|------|
|+|Addition - adds values on either side of the operator.|2 + 1 returns 3|
|-|Subtraction - Subtracts right hand operand from left hand operand.|2 - 1 returns 1|
|\*|Multiplication - Multiplies values on either side of the operator.|2 * 1 returns 2|
|/|Division - Divides left hand operand into right hand operand.|2 / 1 returns returns 2|
|%|Modulus - Divides left hand operand into right hand operand and returns remainder.|2 % 1 returns 0|
|\*\*|Exponent - Performs exponential calculation on operators, the lft operator to the power of the right.|2 \*\* 1 returns 2|

# Comparison Operators

|Operator|Description|Exmaple|
|------|------------|------|
|==|Checks if the value of two operands are equal or not, if yes then condition becomes true.|(a == b) is not true|
|!=|Checks if the value of two operands are equal or not, if values are not equal then condition becomes true.|(a != b) is true|
|>|Checks if the value of the left hand operand is greater than the value of the right operand, if yes then the condition becomes true.| (1 > 2) is false|
|<|Checks if the value of the left hand operand is less than the value of the right operand, if yes then the condition becomes true.| (1 < 2) is true|
|>=|Checks if the value of the left hand operand is greater than or equal to the value of the right operand, if yes then the condition becomes true.| (1 >= 2) is false|
|<=|Checks if the value of the left hand operand is less than or equal tothe value of the right operand, if yes then the condition becomes true.| (1 <= 2) is true|
|<=>|Combined comparison operator. Returns 0 if first operand equals. the second, 1 if the first operator is greater than the second and -1 if the first operator is less than the second.|(1 <=> 2) retuns -1|
|===|Used to test equality within a when clause of a case statement.|(1...10) = 5 returns true|
|.eql?|True if the receiver and argument have both the same type and equal values|1 === 1.0 returns true, but 1.eql?(1.0) is false|
|equal?|True if the receiver and argument have the same object id>|If aObj is a duplicate of bObj the aObj == bObj is true, a.equal?bObj is false but a>equal?aObj is true|

# Assignment Operators

|Operator|Description|Example|
|------|------------|------|
|=| Simple assignment operator, assigns values from right side operands to left side operand.|c = a + b will assign the value of a + b into c|
|+=| Add AND assignment operator, adds right operand to the left operand and assign the result to the left operand.|c ++ a is equalent to c = c + a|
|-=|Subtract AND assignment operator, subtracts right operand from the left operand and assign the result to left operand.|c -= a is equivalent to c = c - a|
|\*=|Multiply AND assignment operator, multiply right operand by the left operand and assign the result to left operand.|c \*= a is equivalent to c = c \* a|
|/=|Divide AND assignment operator, divide right operand into left operand and assign the result to left operand.|c /= a is equivalent to c = c / a|
|%=|Modulus AND assignment operator, divide left operand into right operand and assign the remainder to the left operand.|c %= a is eqvivalent to c = c % a|
|\*\*=|Exponent AND assignment operator, performs expotnential calculation on operators and assign value to the left operand.|c \*\*= a is equvalent to c = c \*\* a|

