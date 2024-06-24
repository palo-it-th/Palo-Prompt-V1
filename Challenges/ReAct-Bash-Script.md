# React Bash Script

## Question

- Set up and install NestJS
- Create a simple web server to serve local files or run a small web application.
- A script that receive human description of llm bot and output detailed instruction for llm bot
- A script that open web browser and take screenshot and do ocr to extract text then put the extract text in json file name extract.json and home directory
- move a mouse in specific location and right click
- Set up NestJs project with 3 apis which are store,pets,owner
- I have fullstack project coming up. I want to use Cypress to do e2e test, React to do frontend, Express nodejs to do backend. The frontend has 3 pages which are 1. login 2. list of product 3. create product. The backend has 3 apis which are 1. /login 2. /list 3. /create Please set up a project for me.

1. Build a simple command-line tool that takes a directory path as input and outputs the total size of all files in that directory and its subdirectories.

2. Create a web scraper that extracts product information (name, price, description) from an e-commerce website and saves the data to a CSV file.

3. Implement a function that takes a string as input and returns a new string with all the vowels removed.

4. Write a script that monitors a specific directory for new files, and when a new file is added, it sends an email notification with the file name and timestamp.

5. Develop a React component that displays a list of items and allows the user to filter the list based on a search input field.

6. Set up a cron job that runs a Python script every day at midnight to backup a specific database to a remote server.

7. Create a Chrome extension that replaces all instances of a specified word on a web page with a different word.

8. Implement a function that takes an array of numbers as input and returns the second-largest number in the array.

9. Write a bash script that checks if a given process is running and, if not, starts the process.

10. Develop a RESTful API using Node.js and Express that allows users to create, read, update, and delete blog posts.

11. Create a Python script that takes a PDF file as input and extracts all the text from the file, saving it to a text file.

12. Implement a function that takes a string as input and returns a new string with all the characters reversed.

13. Write a shell script that checks if a given directory exists and, if not, creates it along with any necessary parent directories.

14. Develop a React Native app that displays a list of contacts and allows the user to add, edit, and delete contacts.

15. Create a Node.js script that reads data from a JSON file, performs some calculations on the data, and writes the results to a new JSON file.

16. Implement a function that takes a string as input and returns true if the string is a palindrome, false otherwise.

17. Write a Python script that takes a directory path as input and compresses all the files in that directory and its subdirectories into a single ZIP file.

18. Develop a React component that displays a tree-like structure of nested data and allows the user to expand and collapse individual nodes.

19. Create a bash script that monitors a specific log file and sends an email notification when a particular error message is logged.

20. Implement a function that takes an array of strings as input and returns a new array with all the duplicate strings removed.

## Prompt

Human: Use the following pieces of context to provide a concise answer to the question at the end. If you don't know the answer, just say that you don't know, don't try to make up an answer.

Instruction: the input instruction you must answer
Thought: you should always think about what to do in bash commands
Action: bash commands
Verification: verification command to check if the action was successful
... (this Thought/Action/Verification can repeat N times)
Thought: I now know the final answer
Bash Script: the bash script to run all actions at once

Instruction:

Instruction: {question}
