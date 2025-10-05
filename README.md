# JS-Strings-2

# Beginner JavaScript Programs

A collection of simple, beginner-friendly **JavaScript** programs demonstrating fundamental concepts such as arithmetic operations, loops, conditionals, number manipulation, and patterns. Perfect for practice, learning, and showcasing on GitHub.

---

## 📂 Files 

## js-strings-1:

* reverse.js
* palindrome.js
* vowelsConsonants.js
* firstNonRepeatingChar.js
* charFrequency.js
* removeSpaces.js
* longestWord.js
* anagram.js
* titleCase.js
* substringOccurrence.js

## js-strings-2:
* `sum.js` — Add two numbers.
* `multiplication.js` — Multiply two numbers or generate a multiplication table.
* `factorial.js` — Calculate factorial of a number.
* `reverse_number.js` — Reverse the digits of a number.
* `even_range.js` — Print even numbers in a given range.
* `fibonacci.js` — Generate Fibonacci series up to `n` terms.
* `sum_of_digits.js` — Find the sum of digits of a number.
* `pattern.js` — Print simple star/number patterns.
* `multiples_3_and_5.js` — Find numbers (or sum) that are multiples of 3 and 5.
* `prime_check.js` — Check if a number is prime.

 

---

## ▶️ How to Run

1. Install **Node.js** (if not already installed).
2. Open a terminal and navigate to the project folder.
3. Run any file with:

```bash
node sum.js
```

Scripts may take input from `prompt()` (in browser) or you can modify them to use `readline`/`process.argv` in Node.js.

---

## 📖 Example (factorial.js)

```javascript
function factorial(n) {
  let result = 1;
  for (let i = 2; i <= n; i++) {
    result *= i;
  }
  return result;
}

const num = 5;
console.log(`Factorial of ${num} = ${factorial(num)}`);
```

---

 
 
