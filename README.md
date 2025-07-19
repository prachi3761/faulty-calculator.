# faulty-calculator.
 Faulty Calculator – JavaScript Fun Project
This JavaScript-based calculator works like a normal calculator most of the time, but there's a twist! With a 10% chance, it intentionally gives you an incorrect result by swapping the operation using a predefined logic.

💡 How It Works:
Prompts the user to enter two numbers and an operation (+, -, *, /).

Uses Math.random() to generate a random number between 0 and 1.

If the number is greater than 0.1, it performs the correct operation.

If the number is 0.1 or less, it performs a "faulty" calculation by replacing the operation:

+ becomes -

- becomes /

* becomes +

/ becomes ** (exponentiation)

This simple project demonstrates JavaScript concepts like prompt, eval, Math.random(), and object-based operation mapping. It's perfect for exploring conditional logic and randomness in a fun way!
