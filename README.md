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
