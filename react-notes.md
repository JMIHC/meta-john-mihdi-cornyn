# React Notes

## On Functions
- Function Declarations benefit from hoisting; can be called before declaration. Function Expressions do not benefit from hoisting and will error when called before declaration.

- Returning an object in an arrow function requires parentheses. 
    Ex: const person = (firstName, lastName) => ({
        first:: firstName,
        last: lastName
    });

