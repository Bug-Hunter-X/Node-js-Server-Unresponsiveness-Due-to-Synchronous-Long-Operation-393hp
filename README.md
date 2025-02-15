# Node.js Server Unresponsiveness

This repository demonstrates a common Node.js issue where a long-running synchronous operation in a request handler causes the server to hang or become unresponsive.  The event loop is blocked, leading to poor performance and potential crashes.

The `server.js` file contains the buggy code, while `serverSolution.js` shows how to resolve the problem using asynchronous operations.