# React useEffect Infinite Loop Bug

This repository demonstrates a common React bug where `useEffect` runs on every render, even with an empty dependency array. This can lead to performance issues and even crashes.  The solution shows the correct way to manage dependencies in `useEffect` to avoid this issue.

## Bug
The `bug.js` file shows the incorrect implementation of `useEffect`.  The console log is called excessively.

## Solution
The `bugSolution.js` file provides the correct implementation.  The dependency array is used to control when the effect runs.