# React Native: Accessing Property of Null or Undefined

This repository demonstrates a common error in React Native applications: attempting to access a property of an object that is null or undefined.  The `bug.js` file shows the problematic code, while `bugSolution.js` provides the corrected version.  This issue often arises when dealing with asynchronous data or components that haven't fully mounted.

**Problem:** Unhandled errors occur when trying to read properties from objects before they're properly populated, leading to crashes or unexpected behavior.

**Solution:** Use conditional checks (e.g., `if` statements, optional chaining) to ensure the object exists and has the desired property before accessing it.