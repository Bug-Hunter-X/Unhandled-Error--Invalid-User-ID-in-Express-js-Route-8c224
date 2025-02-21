# Unhandled Error: Invalid User ID in Express.js Route

This repository demonstrates a common error in Express.js route handlers:  failure to handle cases where input parameters (in this case, a user ID) are not in the expected format.  The provided code attempts to parse a user ID from the request parameters as an integer without adequate error handling, which could result in the application crashing or returning unexpected results if the provided ID is not a valid integer.

The solution demonstrates proper error handling using a `try...catch` block to gracefully manage potential `NaN` errors and respond appropriately to invalid input.