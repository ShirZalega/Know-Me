Markdown
# Know Me

An interactive web application designed to break the ice, deepen relationships, and spark meaningful conversations in a digital world. 
This project combines principles from Computer Science (software architecture and performance) and Neuroscience (the psychology of self-disclosure and emotional connection).

## The Problem & The Solution
In an era of digital overload and superficial "small talk," people struggle to create deep, meaningful connections—even with those closest to them. **Know Me** solves this by turning the process of getting to know someone into a fun game. Through gamification elements (rolling a dice, taking shots), the app lowers social barriers and provides a safe, comfortable structure for face-to-face, deep conversations.

## Key Features

* **Smart Non-Repeating Algorithm:** A state management system that tracks previously asked questions, ensuring every game round feels fresh and surprising.
* **Responsive & Minimalist Design (Boho-Chic):** A clean, calming UI built with CSS variables, fully optimized for all screen sizes (Mobile First).
* **Adaptive Loading & Performance:** Automatically detects network quality or battery-saving modes (using the Network Information API) and triggers a "Lite Mode." This disables heavy animations and shadows to ensure smooth performance on slow connections.
* **Pure CSS 3D Dice:** An interactive, realistic 3D dice built entirely with HTML and CSS—no heavy images required—complete with physics-based spin animations.
* **Dynamic Shot Counters:** A customized tracking system tailored to the game mode (visual glasses for couples, a numeric group counter for friends).

## Game Modes

1. **Couples:** Deep questions, intimacy, nostalgia, and relationship-building. The app's background color dynamically changes based on the rolled category.
2. **Friends:** Lighthearted questions, icebreakers, funny dilemmas, and a group shot counter to elevate the vibe.
3. **Family:** A safe space for sharing feelings, family memories, and strengthening intergenerational bonds (completely alcohol-free).

## The Scientific Angle (Neuro-Connection)
The question bank wasn't chosen at random. It is based on the **Gradual Self-Disclosure principle (The Fast-Friends Technique)**. 
The element of surprise from rolling the dice triggers **dopamine** release, while deep questions and active listening promote **oxytocin** production. This combination creates a rapid, strong neurological connection, builds trust, and reduces social anxiety in real-time.

## Tech Stack

* **Front-End:** HTML5, CSS3 (Flexbox, CSS Variables, Media Queries, 3D Animations)
* **Logic:** Vanilla JavaScript (ES6+)
* **Performance APIs:** Network Information API, `matchMedia` for accessibility (Reduced Motion)
* **No Frameworks:** Built with Pure JS and CSS to ensure near-zero loading times and minimal dependency on external libraries.

## Installation & Usage

This project requires no backend server or complex installation. 
1. Clone or download the repository.
2. Open the `index.html` file in any modern browser (Chrome, Safari, Firefox).
3. **Recommended:** Open on a mobile device or use Developer Tools in your browser to fully experience the responsive design.
