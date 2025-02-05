# React Router: Missing Catch-All Route

This repository demonstrates a common issue in React Router applications:  the lack of a catch-all route to gracefully handle invalid or non-existent paths.  Without a catch-all, React Router might display unexpected behavior when a user tries to navigate to a URL that doesn't match any defined routes, potentially leading to a blank screen or an error.

The `App.js` file shows the buggy code, which lacks a `Route` to handle unmatched paths.  The `AppSolution.js` demonstrates the solution: adding a catch-all `Route` using the `*` wildcard, effectively creating a 404 page.