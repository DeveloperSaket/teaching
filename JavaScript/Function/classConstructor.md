A JavaScript class that utilizes a constructor to create objects:

```javascript
class Person {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }

  greet() {
    console.log(`Hello, my name is ${this.name}. I am ${this.age} years old.`);
  }
}

// Creating an instance of the Person class
const person1 = new Person("Alice", 30);

// Accessing properties and methods
console.log(person1.name); // Output: Alice
console.log(person1.age); // Output: 30
person1.greet(); // Output: Hello, my name is Alice. I am 30 years old.
```

**Explanation:**

1. **Class Definition:** The `Person` class is defined using the `class` keyword.
2. **Constructor:** The `constructor` method is called when a new instance of the class is created. It takes two parameters, `name` and `age`, and assigns them to the corresponding properties of the object using the `this` keyword.
3. **Instance Creation:** The `new` keyword is used to create a new instance of the `Person` class, passing the desired values for `name` and `age`.
4. **Property Access:** The `name` and `age` properties can be accessed using dot notation.
5. **Method Invocation:** The `greet` method is defined within the class and can be called on the instance using dot notation.

This code demonstrates how to create a class and its instances, using the constructor to initialize properties and define methods.
