# nextleveldev-Assignment-1


#What is Type Inference in TypeScript? 

This is describing the way in which TypeScript can take a variable, something that is there to be another: a function returns something or an expression throws up an error if used with incompatible types; if you do not explicitly declare it, it does not type it.

Example:

let count = 5;  // TypeScript infers count to be a number

Here you did not say "let count: number." Since you assigned 5 to count, TypeScript knows count is a number.

#The Importance of Type Inference
1. Less Code, More Safety
This withheld the developer from explicitly writing types, which made the code clean and concise — all type-safe.

2. Good Developer Experience
The editor will provide better autocomplete, refactoring, and error checking because TypeScript knows the types behind your code.

3. Early Error Detection
Detects type-related errors early on, even without having explicit types, preventing the occurrence of bugs.

4. Smooth Learning Curve
Beginners can write code in JavaScript style but are gradually exposed to the benefits of static typing.
