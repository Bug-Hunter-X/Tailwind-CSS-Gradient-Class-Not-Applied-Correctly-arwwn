# Tailwind CSS Gradient Class Bug

This repository demonstrates a bug in Tailwind CSS where gradient classes with custom color values are not applied correctly.

## Bug Description
The `bg-gradient-to-r-from-blue-500-to-red-500` class does not produce the expected gradient.  This is because the class is expecting the standard Tailwind colors, not custom RGB values.

## Solution
The solution is to use Tailwind's built-in color system, or define your custom colors using Tailwind's configuration system.

## Reproduction Steps
1. Create a new project with Tailwind CSS.
2. Add the code from the `bug.js` file to your project.
3. Observe that the gradient class is not applied correctly.

## How to fix the bug
1. Use Tailwind's built-in colors, or 
2. Define custom color values in your `tailwind.config.js` file.
