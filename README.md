# JavaScript Basics — Practice Examples

## 1. Reverse a String

```js
const str = "Madam";

const result = str.split("").reverse().join("");

console.log(result); // "madaM"
```

**Methods used:** `split()`, `reverse()`, `join()`

## 2. Check Palindrome

A palindrome reads the same forward and backward.

```js
const str = "Madam";

const reversed = str.toLowerCase().split("").reverse().join("");

const result = str.toLowerCase() === reversed;

console.log(result); // true
```

## 3. Find the Largest Number

```js
const nums = [12, 11, 12, 14, 645, 199];

const result = Math.max(...nums);

console.log(result); // 645
```

**Concepts used:** `Math.max()` and the spread operator (`...`).

## 4. Count Vowels

```js
const str = "FaizanRasheed";

const vowels = str.match(/[aeiou]/gi);

const result = vowels ? vowels.length : 0;

console.log(result); // 6
```

**Concepts used:** Regular expressions, `match()`, and the ternary operator.

## 5. Remove Duplicate Values

```js
const nums = [1, 2, 4, 5, 6, 6, 7, 8, 8, 8];

const result = [...new Set(nums)];

console.log(result); // [1, 2, 4, 5, 6, 7, 8]
```

**Concepts used:** `Set` and the spread operator.

## Practice Questions

1. Reverse `"JavaScript"`.
2. Check whether `"Racecar"` is a palindrome.
3. Find the largest number in `[3, 99, 12, 45]`.
4. Count vowels in `"Hello World"`.
5. Remove duplicates from `[2, 2, 3, 4, 4, 5]`.

## How to Run

1. Create a file named `basics.js`.
2. Copy any example into it.
3. Run it using Node.js:

```bash
node basics.js
```

4. Predict the output before running each example.
