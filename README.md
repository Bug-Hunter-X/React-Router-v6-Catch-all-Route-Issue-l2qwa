# React Router v6 Catch-all Route Issue

This repository demonstrates a common issue with catch-all routes (`/*`) in React Router v6.  The catch-all route unintentionally overrides more specific routes.  The solution provides a correct implementation that prioritizes specific routes over the catch-all.

## Problem
The provided `App.js` shows a basic React Router setup with a Home, About, and NotFound component. The catch-all route (`/*`) intended to catch any invalid routes is incorrectly capturing all requests, including those for `/` and `/about`.