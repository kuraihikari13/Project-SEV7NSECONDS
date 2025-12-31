# PROJECT SEV7NSECONDS
#### Video Demo : https://youtu.be/Crs41sXmz6s
#### Description :

A Cinematic Frontend Portfolio Experience

CS50 Final Project

Overview

PROJECT SEV7NSECONDS is a cinematic, frontend-only web project created as my final submission for CS50.
Rather than functioning as a traditional website, this project is designed as an experience-first digital portfolio, tailored especially for digital artists and creatives who want to present their work in a memorable and immersive way.

The site behaves more like an animated intro sequence than a conventional webpage. The user is guided through a sequence of transitions, glitch effects, and timed reveals before reaching the main content — much like the opening moments of a film or game.

This project runs entirely on the client side, using only HTML, CSS, JavaScript, and Vue.js, with no backend, API, or database involved.

Project Motivation

The core motivation behind this project was a simple question:

How can a portfolio feel like a story, not just a collection of links?

Inspiration was drawn heavily from Cyberpunk: Edgerunners, particularly its use of:

Abrupt transitions

Visual glitches as storytelling tools

Text and UI elements that feel unstable, alive, and emotional

Silence and timing used as dramatic devices

Rather than treating glitches as errors, this project embraces them as intentional design language, representing themes of identity, memory, and digital legacy.

This approach fits naturally with the idea of a digital artist portfolio, where atmosphere and emotion are just as important as content.

Concept: A Portfolio as an Experience

This website is designed as a sample portfolio for a digital artist, not as a final commercial product.

The goal is to demonstrate how:

A portfolio can feel cinematic

Transitions can convey mood

Minimal content can still leave a strong impression

Frontend logic can support storytelling

Instead of overwhelming the user with information, the site:

Introduces itself slowly

Builds anticipation

Uses animation to guide attention

Allows the visuals to breathe

Technologies Used

HTML — Semantic structure and layout

CSS — Styling, transitions, flicker effects, and layout

JavaScript — Timing logic, text scrambling, interaction handling

Vue.js (via CDN) — State management and conditional rendering

Why Vue via CDN?

Vue was included using a CDN instead of a full npm-based setup in order to:

Keep the project lightweight

Avoid build tools and configuration overhead

Make the project easy to run and review

Focus on logic and interaction rather than tooling

This decision also makes the project more accessible to beginners.

Key Features
Cinematic Intro Sequence

Scrambled text glitch animation for the title

Scrambled glitch animation for the entry button

Subtle flicker effect after resolution

Carefully timed reveals to allow animations to complete

Phase-Based Flow

The site progresses through several phases:

Start Screen – title and button introduction

Intro Sequence – audiovisual transition

Glitch Overlay – brief disruption before entering

Main Interface – portfolio content

Each phase is controlled using Vue’s reactive state.

Text-Based Glitch Effects

Characters scramble and resolve progressively

No RGB color distortion

Focus on motion, timing, and readability

Inspired by cyberpunk UI aesthetics rather than error simulation

Portfolio-Style Navigation

The main interface includes multiple sections such as:

Home

Portfolio

Contact

Each section uses animated transitions and glitch effects to maintain visual consistency.

Project Structure

The entire project exists inside a single HTML file.

This was a deliberate design choice to:

Keep the project portable

Make it easy to open and review

Reduce unnecessary complexity

Highlight logic and animation rather than file structure

Despite being a single file, the code is separated into clear sections:

Markup

Styling

Vue application logic

Reusable animation functions

How It Works
Vue State Management

Vue controls:

Which phase is currently active

When elements appear or disappear

When animations begin and end

When user interaction is enabled

This makes the UI predictable and avoids manual DOM manipulation wherever possible.

Text Scramble Logic

The glitch effect works by:

Replacing characters with random symbols

Gradually locking correct characters into place

Updating the text at short time intervals

Ending with a subtle flicker animation

This creates the illusion of unstable data resolving into meaning.

How to Run the Project

No installation is required.

Clone or download the repository

Open index.html in a modern browser

Enable audio for the full experience

That’s all.

Educational Value

This project demonstrates:

Frontend animation techniques

JavaScript timing and control flow

Vue conditional rendering

UI state transitions

How design inspiration can shape technical decisions

It also shows how non-traditional websites can still be valid and effective CS50 projects.

Future Improvements

Possible future enhancements include:

Mobile responsiveness

Accessibility options

User-controlled animation toggles

Backend integration for dynamic portfolios

Localization and language support

These were intentionally left out to keep the scope appropriate for CS50.

Final Thoughts

PROJECT SEV7NSECONDS is an exploration of how frontend technologies can be used not just to display content, but to tell a story.

Inspired by cyberpunk aesthetics and designed as a digital artist portfolio, this project focuses on mood, timing, and presence rather than raw complexity.

This was PROJECT SEV7NSECONDS.
This was CS50.
