# React Native: Uninitialized State Variable Access

This repository demonstrates a common error in React Native: accessing a state variable before it has been initialized. This often occurs when using the `useState` hook in functional components.  The problem is that the initial render of a component may attempt to use a state variable that hasn't yet had a value assigned.  This results in undefined values and can lead to crashes or unexpected behavior.

The `bug.js` file shows the erroneous code. The `bugSolution.js` file provides a corrected version.