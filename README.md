# Tailwind CSS PurgeCSS Configuration Error

This repository demonstrates an uncommon bug in Tailwind CSS related to an incorrect PurgeCSS configuration.  The problem is that the `purge` option in `tailwind.config.js` is missing some source files, causing the build process to remove styles that are actually used in the application. This results in missing styles in the production build.

## Steps to Reproduce

1. Clone this repository.
2. Install dependencies using `npm install`.
3. Attempt to build your application. You will likely notice missing styles.

## Solution

The solution involves correctly configuring the `purge` option in `tailwind.config.js` to include all necessary source files.  Review the `bugSolution.js` file for the corrected configuration. 
