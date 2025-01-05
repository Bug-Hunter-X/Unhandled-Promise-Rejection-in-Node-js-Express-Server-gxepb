# Unhandled Promise Rejection in Node.js Express Server
This repository demonstrates a common error in Node.js applications: unhandled promise rejections.  The bug.js file contains an Express server that simulates an asynchronous operation which sometimes throws an error.  The error is not handled properly, leading to a crash.
The bugSolution.js file provides a solution using a try...catch block or promise error handling to gracefully manage the exception and prevent the server from crashing.
## How to reproduce
1. Clone this repository.
2. Run `npm install` to install Express.
3. Run `node bug.js` to start the server and observe the behavior.
4. Run `node bugSolution.js` to see the fixed version.