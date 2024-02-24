# Minimal Reproduction of Error in uiwjs/react-heat-map

This repository contains a minimal reproduction of an error encountered in the [uiwjs/react-heat-map](https://github.com/uiwjs/react-heat-map) project.

## Error Description

The error is a warning message that appears when a props object containing a "key" prop is being spread into JSX. This is generally considered an anti-pattern in React as it can lead to unexpected behavior.

## Steps to Reproduce

1. Clone this repository.
2. Install the dependencies using `npm install`.
3. Run the project using `npm run dev`.
4. Observe the console for the warning message.