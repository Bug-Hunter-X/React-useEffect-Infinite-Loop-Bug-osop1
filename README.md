# React useEffect Infinite Loop Bug

This repository demonstrates a common bug in React applications involving the `useEffect` hook and its dependency array.  The example showcases an infinite loop caused by incorrectly specifying the dependency array, leading to performance issues and unexpected behavior.

## Bug Description

The `useEffect` hook is used to perform side effects, like setting up timers or fetching data.  A crucial part of `useEffect` is its dependency array.  If a dependency is missing, the effect will run on every render, leading to unintended consequences.

## Solution

The solution involves correctly specifying the `count` variable in the dependency array. This ensures the effect only runs when `count` changes.
