# Blueprint: Lotto Number Generator

## Overview

This is a modern, responsive web application that generates random lottery numbers (Lotto 6/45). It features a sleek design with support for both dark and light modes.

## Features

*   **Lotto Generation:** Generates 6 unique random numbers between 1 and 45.
*   **Theme Toggle:** Supports dark and light modes with persistent user preference using `localStorage`.
*   **Responsive Design:** Optimized for various screen sizes using a modern flexbox layout.
*   **Interactive UI:** Smooth transitions and hover effects for a premium feel.

## Design & Style

*   **Layout:** Centered container with a clean, minimalist header and a grid of numbers.
*   **Typography:** Uses 'Inter' system font stack for maximum readability and a modern aesthetic.
*   **Colors (Light Mode):**
    *   Background: `#f8fafc`
    *   Container: `#ffffff`
    *   Accent: `#3b82f6` (Blue)
*   **Colors (Dark Mode):**
    *   Background: `#0f172a`
    *   Container: `#1e293b`
    *   Accent: `#60a5fa` (Light Blue)
*   **Visual Effects:** Soft multi-layered shadows and smooth color transitions.

## Implementation Steps

1.  **CSS Variables:** Implemented a robust color system using CSS variables for easy theme switching.
2.  **Theme Logic:** Added JavaScript to toggle the `.dark-mode` class and save the state to `localStorage`.
3.  **UI Polish:** Enhanced the buttons, cards, and typography for a professional look.
