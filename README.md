# ΛLΞX JΛMΞS ᗪEV

This project is an **interactive portfolio and realistic typing effect** web application, designed to showcase a modern, immersive UI experience. It features a clean, dark-themed aesthetic with animated flower backgrounds, firefly particle effects, and a highly customizable "human-like" typing animation.

### Live Demo
[https://glowing-flower-alex.vercel.app](https://glowing-flower-alex.vercel.app)

## Features

*   **Interactive Typing Effect**: Realistic typing behavior with variable delays, mimicking human input.
*   **Voice Integration**: Built-in support for the Web Speech API, allowing users to type via voice commands (in Bangla).
*   **Immersive Visuals**:
    *   Animated floral background (via `iframe`).
    *   Interactive particle system (`canvas`) including glowing heart effects.
    *   Smooth Canva-style animated modal overlays for input.
*   **Mobile-Friendly**: Responsive design with specialized handling for mobile keyboard appearance and layout shifts.
*   **User Controls**:
    *   **Auto-Type**: Input custom text to be animated on-screen.
    *   **Voice Input**: Start microphone to type speech to text.
    *   **Clear**: Word-by-word dissolution animation for clearing the screen.
    *   **Portfolio Link**: Easy access to the main portfolio URL.

## Technical Stack

*   **Frontend**: HTML5, CSS3, JavaScript (Vanilla).
*   **Fonts**: Google Fonts (`Poppins`, `Anek Bangla`).
*   **APIs**:
    *   **Web Speech API**: For voice-to-text functionality.
    *   **Canvas API**: For custom particle and typing animations.
    *   **Visual Viewport API**: For handling mobile keyboard layout adjustments.
*   **Design**: Modern UI with backdrop filters, glassmorphism, and custom animations.

## Usage

1.  **Clone the repository** (or host the HTML file).
2.  **Open in a browser**: The page uses modern browser APIs; for the best experience, use a modern desktop or mobile browser.
3.  **Interaction**:
    *   **Click the Play button** to open the modal and type text for the auto-typing simulation.
    *   **Click the Mic button** to trigger voice input.
    *   **Click the Delete Sweep button** to clear your input with a smooth visual effect.
    *   **Click the Person icon** to visit the primary portfolio website.

## Licensing
This project is for personal portfolio demonstration. Please ensure you have permission to use any assets linked from third-party sources (e.g., external `iframe` content).
