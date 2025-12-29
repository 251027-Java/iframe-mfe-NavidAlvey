[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/FBFREOhF)
# Lab: Simple Micro-Frontends with iFrames

## Goal
Build a "Shell" application that integrates two external websites as Micro-Frontends using the simplest possible technique: iFrames.

## Requirements
1.  **Shell**: Create `index.html`.
    -   Layout: Header (Global Navigation), Sidebar, Main Content Area.
2.  **Navigation**:
    -   Clicking "App 1" in sidebar loads `page1.html` into the Main Content iFrame.
    -   Clicking "App 2" loads `page2.html`.
3.  **Communication (Bonus)**:
    -   Add a button in App 1: "Change Shell Color".
    -   Use `window.parent.postMessage()` to send a message to the Shell.
    -   Shell listens for message and changes background color.

## Starter Code
-   `index.html` (Shell structure).
-   `app1/index.html` (Sub-app).
