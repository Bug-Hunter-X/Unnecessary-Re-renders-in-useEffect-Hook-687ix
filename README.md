# Unnecessary Re-renders in useEffect Hook

This repository demonstrates a common React bug involving the `useEffect` hook. The provided code causes unnecessary re-renders and console logs because the useEffect runs after every render.  This can lead to performance issues and makes debugging more difficult.

The solution shows how to optimize the `useEffect` hook using the dependency array to control when the effect runs. 