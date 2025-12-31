🎬 SEV7NSECONDS’ LEGACY

CS50 Final Project – Cinematic Frontend Website

📌 Overview

SEV7NSECONDS’ LEGACY is a cinematic, frontend-only web project created as my final submission for CS50.

Instead of building a traditional static website or CRUD application, this project explores how animation, timing, and user interaction can be used to create an immersive experience using only client-side technologies.

The website behaves more like a movie intro or system boot sequence than a conventional webpage, guiding the user through animated phases before arriving at the main interface.

No backend, database, or API is used — the entire experience runs directly in the browser.

🎯 Project Goals

The main goals of this project were:

To demonstrate strong frontend fundamentals

To explore animation-driven UI design

To practice state management without a backend

To build something that feels intentional, immersive, and polished

To keep the project lightweight and portable

This project is also designed to be understandable and extendable by beginners.

🛠 Technologies Used

HTML – Structure and semantic layout

CSS – Styling, transitions, and visual effects

JavaScript – Animation logic, timing, and interactions

Vue.js (CDN) – UI state management and conditional rendering

Why Vue CDN?

Vue is included via CDN to:

Avoid build tools and configuration

Keep the project easy to run

Focus on logic and interaction rather than setup

No npm, bundler, or framework installation is required.

🚀 Features
🎞 Cinematic Intro Flow

Scrambled text glitch animation for the title

Scrambled glitch animation for the entry button

Subtle flicker effect after text resolution

Controlled timing to allow animations to fully play

🔀 Phase-Based Navigation

The website progresses through multiple phases:

Start screen

Intro sequence

Glitch transition

Main interface

Each phase is controlled using Vue state and conditional rendering.

🧠 Text-Based Glitch Effects

No RGB color distortion

Characters scramble and resolve progressively

Effects feel deliberate and readable

Implemented using custom JavaScript logic

📂 Tab-Based Main Interface

Home

Portfolio

Contact

Each tab triggers:

Animated text updates

UI transitions

Sound and visual feedback

🧩 Project Structure

The entire project lives inside a single HTML file.

This was a deliberate decision to:

Keep the project portable

Make it easy to review

Reduce complexity

Emphasize logic and behavior over tooling

Despite being a single file, the code is organized into logical sections:

HTML layout

CSS effects

Vue application logic

Reusable animation functions

🧪 How It Works
Vue State Management

Vue is used to control:

Which screen is visible

When animations start

When buttons become interactive

When transitions occur

Instead of manually manipulating the DOM everywhere, Vue keeps the UI predictable and readable.

Glitch Animation Logic

The text glitch effect works by:

Replacing characters with random symbols

Gradually locking characters into their correct position

Updating the DOM at short intervals

Ending with a subtle flicker effect

This approach focuses on motion and timing, not heavy visual effects.

🖥 How to Run the Project

No installation required.

Clone or download the repository

Open index.html in any modern browser

Make sure audio is enabled for the full experience

That’s it.

🎓 Educational Value

This project demonstrates:

Frontend animation techniques

JavaScript timing and intervals

Vue conditional rendering

UI state transitions

Separation of logic and styling

How small details improve user experience

It also serves as a foundation that can be extended into:

A full portfolio

A game intro

A storytelling website

A personal brand landing page

🔮 Possible Improvements

If expanded further, this project could include:

Mobile optimization

Accessibility improvements

Performance optimizations

Backend integration

User-controlled animation settings

Localization support

These were intentionally left out to keep the scope appropriate for CS50.

🧾 Acknowledgements

Inspired by cinematic UI design and system boot sequences

Built as part of CS50

Thanks to the CS50 staff for providing a strong foundation in computer science

🏁 Final Notes

This project was created to explore how far frontend technologies alone can go when attention is paid to detail, timing, and user experience.

Rather than focusing on complexity, the emphasis was placed on clarity, control, and immersion.

This was SEV7NSECONDS’ LEGACY.
This was CS50.
