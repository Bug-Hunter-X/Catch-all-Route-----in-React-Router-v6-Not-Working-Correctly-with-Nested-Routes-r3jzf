# React Router v6 Catch-all Route Issue

This repository demonstrates a problem with React Router v6's catch-all route (`*`) when used within nested routes.  The `NotFound` component, intended to handle invalid URLs, fails to display correctly.

## Problem
The issue occurs when a catch-all route is nested. Despite having a route that matches any path, the application routes to components other than the `NotFound` component.

## Solution
The solution involves ensuring correct route placement to properly handle routes for different states.  See the `bugSolution.js` file for a working implementation.