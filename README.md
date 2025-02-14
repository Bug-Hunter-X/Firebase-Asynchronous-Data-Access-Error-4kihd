# Firebase Asynchronous Data Access Error

This repository demonstrates a common error in Firebase applications: attempting to access data before asynchronous operations, such as fetching data from the Realtime Database or Cloud Firestore, have completed.  This leads to undefined behavior or errors.

The `firebaseBug.js` file showcases the problematic code, resulting in an error.  `firebaseBugSolution.js` provides the corrected code, using promises or async/await to handle asynchronous operations properly.

## Setup

1.  Ensure you have Node.js and npm installed.
2.  Install the Firebase JavaScript SDK: `npm install firebase`
3.  Configure your Firebase project and replace placeholders in the code with your project's configuration.

## How to Run

1.  Clone this repository.
2.  Navigate to the repository's directory in your terminal.
3.  Run `node firebaseBug.js` to see the error.
4.  Run `node firebaseBugSolution.js` to see the corrected code in action.