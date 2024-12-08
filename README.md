# Node.js Server Crashing Under High Load

This repository demonstrates a common issue in Node.js applications: crashing under high load due to unhandled exceptions or resource exhaustion.  The `bug.js` file contains the faulty server code. The `bugSolution.js` file provides a solution using a more robust approach for handling concurrent requests. 

## Problem

The initial server implementation is simple, but it lacks proper error handling and doesn't scale well. When bombarded with many requests simultaneously, it's prone to crashing.