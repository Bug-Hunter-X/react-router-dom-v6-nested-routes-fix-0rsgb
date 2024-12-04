# React Router Dom v6 Nested Routes Bug

This repository demonstrates a bug encountered when using nested routes in React Router Dom v6.  The issue revolves around parameters not being passed correctly to nested route components.

## Bug Description

When navigating to nested routes, parameters are not correctly passed to the nested component. This can lead to unexpected behavior or errors in the application.

## Bug Reproduction

1. Clone this repository.
2. Install dependencies using `npm install`.
3. Run the application using `npm start`.
4. Navigate to a nested route.
5. Observe that the parameters are not being passed to the nested component, resulting in the nested component not rendering correctly.

## Solution

The solution involves using the `useParams` hook correctly within the nested component to access the parameters from the URL.