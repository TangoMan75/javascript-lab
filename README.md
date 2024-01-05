![GH language](https://img.shields.io/github/languages/top/TangoMan75/javascript-lab)
[![GH release](https://img.shields.io/github/v/release/TangoMan75/javascript-lab)](https://github.com/TangoMan75/javascript-lab/releases)
[![GH license](https://img.shields.io/github/license/TangoMan75/javascript-lab)]((https://github.com/TangoMan75/javascript-lab/blob/master/LICENSE))
[![GH stars](https://img.shields.io/github/stars/TangoMan75/javascript-lab)](https://github.com/TangoMan75/javascript-lab/stargazers)
[![Node CI](https://github.com/TangoMan75/javascript-lab/workflows/Node%20CI/badge.svg)](https://github.com/TangoMan75/javascript-lab/actions/workflows/node.yml)
![visitors](https://visitor-badge.glitch.me/badge?page_id=TangoMan75.javascript-lab)

🔬 TangoMan Javascript Lab
==========================

#back-end #interview #practice #php #technical-interview #test #training #vanilla

**🔬 TangoMan Javascript Lab** is a Javascript coding project for practicing common interview questions and coding challenges.

There are various Javascript scripts in the root directory that implement different algorithms and solutions to coding problems:

1. 🔄 **Ackermann**

Implements the Ackermann function, which is a classic example of a recursive function that can be used to test compilers and illustrate the concept of recursion.

2. 🔍 **BinarySearch**

Implements binary search to find an element in a sorted array. Binary search is an efficient algorithm for searching sorted data sets and relies on the divide-and-conquer technique.

3. ➕ **Factorial**

Calculates factorials recursively. Factorials are used in combinatorics and provide good examples of recursive functions.

4. 🔢 **Fibonacci**

Generates Fibonacci numbers recursively. The Fibonacci sequence illustrates recursion and has applications in mathematics and nature.

5. 💬 **FizzBuzz**

Prints numbers 1 to 100, but prints "Fizz" for multiples of 3, "Buzz" for multiples of 5, and "FizzBuzz" for multiples of both. This is a common interview screening question.

6. 👋 **HelloWorld**

Prints "Hello world!" - the traditional first program for beginner programmers.

7. ❄️ **MinTemperature**

Finds minimum temperature value from temperature data. Demonstrates algorithms for finding minimum/maximum values.

8. 🔄 **Palindrome**

Checks if a string is a palindrome. Palindromes illustrate recursion and string manipulation.

9. ✔️ **Perfect**

Checks if a number is a perfect number, where the number equals the sum of its divisors. Interesting math and recursion example.

10. 🃏 **Poker**

Evaluates poker hands. Involves evaluating combinations and ranks of cards.

11. 🥇 **PrimeNumbers**

Checks if a number is prime, where a natural number greater than 1 has no positive divisors other than 1 and itself.

12. 🔄 **Rot13**

Encodes/decodes a string using the ROT13 cipher, a simple letter substitution cipher. Basic encryption example.

13. 🔑 **SimpleJWT**

Implements JSON Web Token (JWT) encoding and decoding.

14. 💹 **Stocks**

Return an array holding the names of the top three stocks with the best average performance given two separate arrays containing stocks names and prices.

15. 🔢 **Syracuse**

Implements the Syracuse algorithm/sequence. Interesting recursion and number theory example.

16. 🏗️ **TowerOfHanoi**

Implements the Tower of Hanoi algorithm. A classic algorithm that illustrates recursion and dynamic programming.

17. 🔄 **VonNeumann**

Generates Von Neumann ordinal numbers. Illustrates generating recursive sequences.

## ✅ Unit Tests

The `tests` directory in each folder contains test cases for testing the implementations of each algorithm.

## 🚀 Github Actions

This project uses Github Actions for continuous integration and testing. The `.github/workflows` directory contains YAML workflow definitions for:

- Linting: Runs `ESLint` to check code style and quality on every push and pull request.
- Testing: Runs `mocha` unit tests.

The workflows help maintain code quality and ensure the tests pass on multiple php versions.

## 📑 Documentation

Chai documentation is available here: [https://www.chaijs.com/guide](https://www.chaijs.com/guide)

Mocha documentation is available here: [https://mochajs.org/](https://mochajs.org)

ESLint documentation is available here: [https://eslint.org/docs/latest/use/getting-started](https://eslint.org/docs/latest/use/getting-started)

## 🌟 Inspiration

The following YouTube videos inspired the Javascript Lab project:

- [FizzBuzz: One Simple Interview Question](https://www.youtube.com/watch?v=QPZ0pIK_wsc)
- [Solve This Coding Question To Win $200](https://www.youtube.com/watch?v=WDuZ_S_9vLg)
- [The Most Difficult Program to Compute? - Computerphile](https://www.youtube.com/watch?v=i7sm9dzFtEI)

💻 Dependencies
---------------

**TangoMan Javascript Lab** requires the following dependencies:

- Node.js
- npm

### 🦖 Node.js

#### 🐧 Install Node.js (Linux)

On linux machine install node globally with the following commands (requires curl):

```bash
$ curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
$ sudo apt-get install --assume-yes nodejs
```

#### 🏁 Install Node.js (Windows)

Download and install recommended LTS version from here: [Node.js](https://nodejs.org/en/download)

#### 🍎 Install Node.js (OSX)

Download and install recommended LTS version from here: [Node.js](https://nodejs.org/en/download)

---

🔥 Usage
--------

Run `sh entrypoint.sh` to print help

Run tests:

```bash
sh entrypoint.sh unit
```

Lint code:

```bash
sh entrypoint.sh lint
```

Fix lint errors:

```bash
sh entrypoint.sh lint --fix
```

Uninstall:

```bash
sh entrypoint.sh uninstall
```

🤝 Contributing
---------------

Thank you for your interest in contributing to **Factorial**.

Please review the [code of conduct](./CODE_OF_CONDUCT.md) and [contribution guidelines](./CONTRIBUTING.md) before starting to work on any features.

If you want to open an issue, please check first if it was not [reported already](https://github.com/TangoMan75/javascript-lab/issues) before creating a new one.

📜 License
----------

Copyrights (c) 2024 &quot;Matthias Morin&quot; &lt;mat@tangoman.io&gt;

[![License](https://img.shields.io/badge/Licence-MIT-green.svg)](LICENSE)
Distributed under the MIT license.

If you like **Factorial** please star, follow or tweet about it:

[![GitHub stars](https://img.shields.io/github/stars/TangoMan75/javascript-lab?style=social)](https://github.com/TangoMan75/javascript-lab/stargazers)
[![GitHub followers](https://img.shields.io/github/followers/TangoMan75?style=social)](https://github.com/TangoMan75)
[![Twitter](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2FTangoMan75%2Fjavascript-lab)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2FTangoMan75%2Fjavascript-lab)

... And check my other cool projects.
