# Introduction To Typescript

TypeScript is an open-source, object-oriented programing language, which is developed and maintained by Microsoft.

It was introduced by Anders Hejlsberg, a core member of the development team of C# language. TypeScript is a strongly typed superset of JavaScript which compiles to plain JavaScript.


---
# What is TypeScript?
TypeScript is a syntactic superset of JavaScript which adds static typing.
This basically means that TypeScript adds syntax on top of JavaScript, allowing developers to add types. TypeScript is pure object oriented with classes, interfaces and statically typed like C# or Java.

TypeScript is not directly run on the browser. It needs a compiler to compile and generate in JavaScript file. TypeScript is the ES6 version of JavaScript with some additional features.

# Why should I use TypeScript?
JavaScript is a loosely typed language. It can be difficult to understand what types of data are being passed around in JavaScript.

TypeScript offers a type-safe development experience that helps catch errors during development, reducing runtime errors. It provides better tooling support for refactoring and code navigation. Additionally, TypeScript offers optional strict mode for stricter type checking and increased code reliability.

# Pros and Cons
Pros:

* Type safety: TypeScript offers a type-safe development experience that helps catch errors during development, reducing runtime errors and making your code more reliable.
* Better tooling support: TypeScript offers better tooling support for refactoring and code navigation, making it easier to maintain and update your codebase.
* Readability: TypeScript code tends to be more readable and self-documenting due to the use of type annotations, making it easier for other developers to understand and work with your code.

Cons:

* Learning curve: TypeScript has a learning curve, and developers who are not familiar with strongly-typed languages may find it difficult to adopt.
* Compilation time: TypeScript code needs to be compiled to JavaScript before it can be executed, which can add to the development time.
* Overhead: Adding type annotations to your code can add some overhead, and the resulting code may be slightly larger than equivalent JavaScript code.

# Getting Started

* First, ensure you have Node installed globally on your machine.
* Then install the TypeScript compiler globally on your machine by running the following command:
```bash
npm i -g typescript
```
* To check if the installation is successful. Use following command to check version number of typescript.
```bash
tsc -v
```
* Now create file, _**index.ts**_, and write a small program.
```typescript
let a = 0;
console.log(a)
```
* Compile this typescript program to javascript using following command:
```bash
tsc index
```
* Now, Run you compiled javascript file using following command:
```bash
node index
```

> Congratulations, you have made first Typescript program.

---
### From next lesson, we will start doing typescript practically, with real world examples.


**Please ⭐ this Repository and Follow us, <br> Thankyou.**