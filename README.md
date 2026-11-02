# // My first backend server
console.log("Hello World! My first repo is working.");

function greet(name) {
  return `Hello, ${name}! Welcome to Software Development.`;
}

console.log(greet("Junior Dev"));




const express = require('express');
const app = express();

app.get('/', (req, res) => {
  res.send('My first API is working!');
});

app.listen(3000, () => {
  console.log('Server running on port 3000');
});


# My First Project
This is my first repository.

## Tools Used
- GitHub
- JavaScript / Node.js
- VS Code

## What I Learned
- How to create a repo
- How to commit code
- Basics of Software Development

Author: BlessingBeDev
