# CSS3 Transitions, Animations, and Advanced JavaScript Functions

## Objectives

Create smooth CSS transitions and animations.
Use JavaScript functions for dynamic behavior.
Implement local storage for data persistence.

## Instructions
Add CSS animations to elements like buttons or images.

>[!NOTE]
> - Write a JavaScript function that:
> - Stores and retrieves user preferences using localStorage.
> - Implements an animation triggered by user actions.

## Tasks

Create a CSS animation.
Store data in localStorage.
Apply JavaScript to trigger animations.

Happy Coding! 💻✨





<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS3 Animations and Advanced JS</title>
    <link rel="stylesheet" href="animations.css">
    <script src="animations.js" defer></script>
</head>
<body>
    <header>
        <h1>CSS3 Animations & Advanced JavaScript Functions</h1>
    </header>
    
    <main>
        <section id="animation-section">
            <h2>Interactive Button</h2>
            <button id="animate-btn" onclick="triggerAnimation()">Hover Over Me</button>
        </section>
        
        <section id="preferences-section">
            <h2>User Preferences</h2>
            <label for="bg-color">Choose Background Color:</label>
            <input type="color" id="bg-color" onchange="savePreference()">
            <p id="message"></p>
        </section>
    </main>
    
    <footer>
        <p>Happy Coding! 💻✨</p>
    </footer>
</body>
</html>

