# React Router Dom v6 Nested Routes Bug

This repository demonstrates a bug encountered when using nested routes in React Router Dom v6. The issue involves nested routes not rendering correctly, even when the URL matches the expected path. 

## Bug Description
The parent route renders without issue, but its child routes fail to render their components, resulting in a blank screen.  This occurs despite the URL correctly matching the defined nested routes.

## Setup
1. Clone the repository
2. Navigate to the project directory
3. Run `npm install`
4. Run `npm start`

## Reproduction
Navigate to a nested route URL. You will observe that the parent route renders, but the nested route component is not displayed.

## Solution
The solution involves ensuring that the nested routes are correctly structured within the parent route and that the `useParams` hook, if used, is functioning correctly.

## Note
This bug appears to be related to how React Router v6 handles nested routes, specifically in certain configurations or with the use of dynamic routes.
