# TypeScript
Learning me sum TypeScript

What is TypeScript and why learn it?
- TypeScript is a superset of JavaScript.
- Takes JavaScript and adds more to it.

- Browsers can't execute it
- it's complied to JavaScript

How to install TypeScript Globally:
npm install -g typescript 

Complie command:
tsc {name_of_app}.ts

How to setup lite-server: 

Use npm init to create a package.json and update the script section to this:
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "lite-server"
  },

Then run npm start.

Using lite-server in lesson-2 for loading live changes to documents.
npm install --save lite-server

After you recompile your typescript file, lite-server will automaticall update changes without having to refresh the browser.

Defer attribute
- tells the boswer that it should go one with the page and load the script "in the background" then run the script when it loads.

CORE DATA TYPES
- The core primitive types in TypeScript are all lowercase!

- number: no special types like float or int.
-string:  text and can be expressed with 'Hi', "Hi", or `Hi`
- boolean : true,false 

Example with number:
function add(n1: number, n2: number) {
    return n1 + n2;
}

const number1 = 5;
const number2 = 2.8;

const result = add(number1, number2);
console.log(result);

TypeScript executes during development when you complie your code

Type Inference: TypeScript compiler can guess the type of the data based on the type or value that is assigned to a variable.


