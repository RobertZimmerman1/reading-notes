## Programming with JavaScript

---

### Operators

- Assignment Operators: Assignment operators assign a value to the left hand of the operand based upon the value of the right hand of the operand.  As in, x = y.
- Comparison Operators: Comparison operators return a logical answer based on whether the comparison is true.  In one case where the comparison is, is 3 = 'apple', the comparison operator would return the value FALSE.  In another case where the comparison is, 10 = 5 + 5, the comparison operator would return the value TRUE.
- Comparison Operator Syntax: 
    - Assignment ( = ): This is not comparison operator syntax.  It is reserved for assignment operators.
    - Equal ( == ): This checks that the value of the comparison is true.
    - Strict Equal ( === ): This checks that the value and type of the comparison is true.
    - Not Equal ( !== ): This checks that the value of the comparison is not true.
- Arithmetic Operators: Arithmetic operators take numerical values and apply mathematical operators to define a single numerical value. For example: 2 + 2 would return 4.
- Logical Operators: Logical operators return boolean values. They leverage the concepts of "or" and "and" to inspect inputs. An example of a logical operand would be: if it is raining outside, and, the dog is outside, then, bring the dog inside.
    - Operator ( && ): AND
    - Operator ( || ): OR
- Concatenation Operator: The concatenation operator (+) pulls together two string values and returns it as one string. For example: console.log('This is ' + 'a string of words') would print to the console "This is a string of words.
- Ternary Operators: Ternary operators have one of two values based upon a condition. The syntax looks like this: 
    - someCondition ? resultIfTrue : resultIfFalse
- someCondition is the logical test. If the logical test evaluates to truthy, resultIfTrue is returned, if not, resultIfFalse is returned.