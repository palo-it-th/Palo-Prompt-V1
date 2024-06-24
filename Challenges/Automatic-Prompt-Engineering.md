# Automatic Prompt Engineering

## Example 1

Question: Here is the example input output of my LLM bot:
Input: 1+1
Output: 2
Input: 2+2
Output: 4

The instruction I gave is?

Answer:

## Example 2

Here is the example input output of my LLM bot:
Input: Create a frontend for my new landing page
Output: First you must install the necessary dependencies. Then you can start by creating a new React component. You can then add the necessary styles and content to the component. Finally, you can render the component in the main App component.

The instruction I gave is to:

## Example 3

I give my chat bot an instruction to write a bash script and here is input and output from the bot I got
Input: Hi
Output: Hi there

Input: Hello
Output: Hello there

Input: Where are you
Output: Where are you there

The instruction is:

## Example 4

I give my chat bot an instruction
Input: Input to the bot
Output: Output of the bot
Here is input and output from the bot I got

Input: Adds two numbers together.
Output: const add = (a: number, b: number): number => a + b;
Input: Concatenates two strings.
Output: const concatenate = (str1: string, str2: string): string => str1 + str2;
Input: Calculates the square of a number.
Output: const square = (num: number): number => num _ num;
Input: Checks if a number is even.
Output: const isEven = (num: number): boolean => num % 2 === 0;
Input: Converts a string to uppercase.
Output: const toUpperCase = (str: string): string => str.toUpperCase();
Input: Filters out odd numbers from an array.
Output: const filterEvenNumbers = (arr: number[]): number[] => arr.filter(num => num % 2 === 0);
Input: Retrieves the first element of an array.
Output: const getFirstElement = <T>(arr: T[]): T | undefined => arr[0];
Input: Calculates the area of a rectangle.
Output: const calculateArea = (width: number, height: number): number => width _ height;
Input: Checks if a string starts with a given substring.
Output: const startsWith = (str: string, substr: string): boolean => str.startsWith(substr);
Input: Formats a number with a specific number of decimal places.
Output: const formatNumber = (num: number, decimalPlaces: number): string => num.toFixed(decimalPlaces);
Input: Checks if an array contains a specific value.
Output: const includes = <T>(arr: T[], value: T): boolean => arr.includes(value);
Input: Finds the maximum value in an array of numbers.
Output: const findMax = (arr: number[]): number | undefined => arr.length > 0 ? Math.max(...arr) : undefined;
Input: Removes duplicate values from an array.
Output: const removeDuplicates = <T>(arr: T[]): T[] => [...new Set(arr)];
Input: Replaces all occurrences of a substring in a string.
Output: const replaceAll = (str: string, substr: string, replacement: string): string => str.replace(new RegExp(substr, 'g'), replacement);
Input: Sorts an array of numbers in descending order.
Output: const sortDescending = (arr: number[]): number[] => arr.sort((a, b) => b - a);
Input: Calculates the factorial of a number.
Output: const factorial = (num: number): number => num <= 1 ? 1 : num _ factorial(num - 1);
Input: Checks if a string is a palindrome.
Output: const isPalindrome = (str: string): boolean => str === str.split('').reverse().join('');
Input: Converts a string to a number.
Output: const toNumber = (str: string): number => parseFloat(str);
Input: Finds the longest string in an array of strings.
Output: const findLongestString = (arr: string[]): string | undefined => arr.reduce((longest, current) => current.length > longest.length ? current : longest, '');
Input: Generates a random integer between two values (inclusive).
Output: const getRandomInt = (min: number, max: number): number => Math.floor(Math.random() _ (max - min + 1)) + min;

The instruction I gave to the bot is
->

## Example 5

I give my chat bot an instruction to write a bash script and here is input and output from the bot I got

Input: "What is the capital of France?",
Output: {
"answer": "The capital of France is Paris."
}
Input: "How many planets are in our solar system?",
Output: {
"answer": "There are 8 planets in our solar system: Mercury, Venus, Earth, Mars, Jupiter, Saturn, Uranus, and Neptune."
}
Input: "What is the tallest mammal?",
Output: {
"answer": "The tallest mammal is the giraffe."
}
Input: "Who wrote the play 'Romeo and Juliet'?",
Output: {
"answer": "The play 'Romeo and Juliet' was written by William Shakespeare."
}
Input: "What is the largest ocean on Earth?",
Output: {
"answer": "The largest ocean on Earth is the Pacific Ocean."
}

The instruction is
