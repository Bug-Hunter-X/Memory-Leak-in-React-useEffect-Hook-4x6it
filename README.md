# React UseEffect Hook Memory Leak

This repository demonstrates a common error in React applications: memory leaks caused by improper use of the `useEffect` hook.  The `bug.js` file contains a component with a setInterval that's not properly cleaned up, leading to a memory leak. The `bugSolution.js` file shows the corrected code with the necessary cleanup function.