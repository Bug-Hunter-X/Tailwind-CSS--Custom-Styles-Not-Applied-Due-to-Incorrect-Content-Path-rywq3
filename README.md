# Tailwind CSS - Custom Styles Not Applied

This repository demonstrates a common issue where custom styles defined in a Tailwind CSS configuration are not applied to components. The problem arises from an incorrect or incomplete `content` path in the Tailwind configuration.

## Problem

The `content` array in the Tailwind configuration may not accurately specify the locations of your template files, causing Tailwind to miss classes and not generate the necessary CSS.

## Solution

Correcting the `content` path to include all relevant template files or folders resolves this issue, ensuring Tailwind can scan and process your custom classes.  Ensure that your paths include all files that reference your custom Tailwind CSS classes.

## Setup

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` (or similar, depending on your setup) to start the development server.

You'll be able to observe the problem and its solution in action.