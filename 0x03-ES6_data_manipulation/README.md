ES6 introduced several new features and methods for data manipulation in JavaScript. These features make it easier and more convenient to work with arrays, objects, and other data structures. Here are some key ES6 features for data manipulation:

1. Array Destructuring: Array destructuring allows you to extract values from an array and assign them to variables in a concise way.

   ````javascript
   const numbers = [1, 2, 3];
   const [a, b, c] = numbers;

   console.log(a); // Output: 1
   console.log(b); // Output: 2
   console.log(c); // Output: 3
   ```

2. Spread Operator: The spread operator (`...`) allows you to expand an array or object into individual elements. It is useful for creating copies of arrays or combining multiple arrays or objects.

   ````javascript
   const array1 = [1, 2, 3];
   const array2 = [...array1, 4, 5, 6];

   console.log(array2); // Output: [1, 2, 3, 4, 5, 6]
   ```

3. Array Methods: ES6 introduced several array methods for performing common operations on arrays in a more concise and expressive way. Some commonly used array methods include:

   - `map()`: Creates a new array by applying a function to each element of an existing array.
   - `filter()`: Creates a new array with elements that pass a certain condition.
   - `reduce()`: Reduces an array to a single value by applying a function to each element.
   - `find()`: Returns the first element in an array that satisfies a provided condition.
   - `forEach()`: Executes a provided function once for each array element.
   - `some()` and `every()`: Check if at least one or every element in an array satisfies a condition, respectively.

4. Object Destructuring: Object destructuring allows you to extract properties from an object and assign them to variables.

   ````javascript
   const person = {
     name: 'John',
     age: 30,
     profession: 'Developer'
   };

   const { name, age } = person;

   console.log(name); // Output: 'John'
   console.log(age); // Output: 30
   ```

5. Object Methods: ES6 introduced several object methods to simplify common object manipulations.

   - `Object.keys()`: Returns an array of an object's own enumerable property names.
   - `Object.values()`: Returns an array of an object's own enumerable property values.
   - `Object.entries()`: Returns an array of an object's own enumerable property key-value pairs as arrays.

6. Set and Map: ES6 introduced two new data structures, `Set` and `Map`, for working with unique values and key-value pairs, respectively. These data structures provide efficient ways to store and manipulate data.

   ````javascript
   const set = new Set();
   set.add(1);
   set.add(2);
   set.add(3);

   console.log(set.has(2)); // Output: true
   console.log(set.size); // Output: 3

   const map = new Map();
   map.set('name', 'John');
   map.set('age', 30);

   console.log(map.get('name')); // Output: 'John'
   console.log(map.size); // Output: 2
   ```

These are just a few of the many ES6 features and methods available for data manipulation in JavaScript. These features help to simplify common tasks, improve code readability, and enhance the overall development experience.
