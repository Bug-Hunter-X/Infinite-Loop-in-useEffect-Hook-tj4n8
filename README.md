# React useEffect Infinite Loop Bug

This repository demonstrates a common bug in React applications involving the `useEffect` hook. The bug causes an infinite loop because of a faulty state update inside the `useEffect` function. 

## Bug Description
The `MyComponent` component uses the `useEffect` hook to update the `count` state. However, the state update logic is incorrect, resulting in a continuous update cycle, leading to an infinite loop.

## Solution
The solution demonstrates how to correctly use the `useEffect` hook to manage state updates without causing infinite loops by using the dependency array to add conditions to when the useEffect runs.