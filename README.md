# React Native Type Mismatch Error

This repository demonstrates a common but easily overlooked error in React Native: type mismatches in component props.  The error arises when a component receives a prop of an unexpected type, leading to unexpected behavior or crashes.  The solution highlights using TypeScript or prop validation to prevent these issues.

## Bug Description
The `MyComponent` expects a numerical `value` prop, but in certain scenarios, it might receive a string instead.  This leads to unexpected behavior and potential crashes.

## Solution
The solution showcases two approaches:

1. **TypeScript:** Adding TypeScript type annotations ensures type safety at compile time, preventing type mismatches.
2. **PropTypes (for legacy projects):** If using TypeScript isn't feasible, `PropTypes` allows you to validate the type of the props at runtime.

This repository provides both examples to demonstrate best practices for avoiding and resolving type mismatch errors in React Native.