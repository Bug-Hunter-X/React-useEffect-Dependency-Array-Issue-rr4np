## React useEffect Dependency Array Issue

This repository demonstrates a common error in React applications involving the `useEffect` hook.  The example shows a component that increments a counter.  The initial implementation forgets to include the state variable (`count`) in the `useEffect` hook's dependency array.  This results in the effect running on every render, leading to unnecessary logging and potential performance problems.

The `bug.js` file contains the buggy code, while `bugSolution.js` provides the corrected version.