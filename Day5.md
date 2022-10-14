# Day 5

## Subjects

- Writing functions
- Accepting parameters
- Returning values
- Parameter labels
- Omitting parameter labels
- Default parameters
- Variadic functions
- Writing throwing functions
- Running throwing functions
- Inout parameters

## Notes

1. We can use internal and external parameter names.
2. In swift we can write code like english language.
3. If function doesn't return a value we don't have to specify anything.
4. We use func keyword to specify a function.
5. Return type have to be written end of the function signature with -> operator.
6. If function body has a only one statement and function has a return type we don't have to write return keyword. The statement will be return statement automatically.
7. We can specify external parameter names with underscore(_). This means we are omitting parameter labels. So we can call that function without parameter labels.
8.  We can set a default parameters for functions. That means if we don't specify parameter when we calling the function the value of parameter is set to default value that we specify when we writing the function.
9. Swift print's function has a default parameter for terminator character and it's value '\n'.
10. Variadic functions can accept any number of parameters.
11. Print function is variadic function. We can pass parameter as much as we want.
12. Swift will convert parameters that we passed in to array. So we can use in function array methods.
13. We can specify that function failure with throws keyword. 
14. We can throw a data with throw keyword and the data must be enum with underline type Error.
15. We can't call throwing function like normal function. We have to use try! or do catch block.
16. Swift function parameters are default constant. If we want to change parameter in function body we have to use inout keyword before parameter data types. So the function can be change the value of input. When we calling inout function we have to use ampersand(&) before the parameter names. 
