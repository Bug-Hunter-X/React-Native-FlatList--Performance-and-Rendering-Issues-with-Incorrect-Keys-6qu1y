# React Native FlatList Key Extraction Bug

This repository demonstrates a common bug in React Native's FlatList component related to improper key extraction. Using the wrong keys can cause rendering inconsistencies and significant performance degradation, especially with large datasets.  This example illustrates the issue and its solution.

## Bug
The `FlatListBug.js` file shows how using an index as a key causes performance issues.  Observe the incorrect rendering and potential performance problems when scrolling.

## Solution
The `FlatListBugSolution.js` file provides a corrected implementation where unique, stable keys (e.g. item IDs) are used.  This results in smooth and correct rendering.  

## How to Reproduce
1. Clone this repository.
2. Run `npm install`
3. Run the app on your emulator or device.  Scroll the list to observe the effects of the incorrect key in `FlatListBug.js` and its correction in `FlatListBugSolution.js`.

This example highlights the importance of providing unique and consistent keys to React Native's FlatList for optimal performance and reliability.