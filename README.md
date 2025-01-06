# React Router Dom Nested Routes Issue

This repository demonstrates a common issue encountered when working with nested routes in React Router Dom v6.  The problem involves a nested route that fails to render correctly due to a path configuration error.  The solution provides a corrected path configuration to resolve the issue. 

## Issue Description

The original code includes a nested route within the Contact component. However, due to an incorrect path specification, the nested route for '/contact/details' does not render, resulting in an unexpected user experience.  The solution demonstrates a corrected approach to resolve this issue.

## Solution

The solution section shows how to correctly define the nested route path using the `useParams` hook for a more robust solution.