# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers: the lack of error handling for invalid input.  Specifically, the `/users/:id` route does not handle cases where `req.params.id` is not a valid integer.  This can lead to unexpected behavior, crashes, or vulnerabilities.

The `bug.js` file shows the problematic code. The `bugSolution.js` file provides a corrected version with robust error handling.