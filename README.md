# pure-react-clock

First React project using “pure React” (without JSX) for learning purposes, no build tools. Made while following a React course!

## Project Demonstration

- Uses `useState` for state management
- Uses `useEffect` for side effects (here, creating a `setInterval` to update the clock every second — note that `setInterval` is a native JavaScript function, not React-specific)
- Demonstrates a clock updating every second

## How it works

- Open `index.html` in a browser
- The clock updates every second

**Note:** This project is made while following a React tutorial and is **not intended for production**.

## How to improve

- Convert to JSX and display actual HTML elements instead of manually creating elements via `React.createElement`
- Clear intervals to avoid memory leaks
