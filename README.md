# Unhandled Exception in Asynchronous Node.js Server

This repository demonstrates a common issue in Node.js applications: unhandled exceptions within asynchronous callbacks causing the server to crash. The `server.js` file shows the problematic code.  The solution, implemented in `serverSolution.js`, uses error handling to prevent crashes and provides graceful degradation.