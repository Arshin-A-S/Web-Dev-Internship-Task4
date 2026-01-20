Task 4- Multi-Page Personal Portfolio Website:
This project marks the completion of a functional, multi-page portfolio website. The primary focus was on expanding a single-page layout into a scalable multi-page structure while maintaining consistent styling and a professional user interface.

Project Scope:
I transformed the initial profile into three distinct pages to organize content logically:

Home (index.html): Features Education and Skills.

About (about.html): Detailed "About Me" biography.

Contact (contact.html): Social links and email contact information.

Key Features & Implementation
1. Multi-Page Navigation
A unified header and nav system was implemented across all files. Using relative linking, I created a seamless transition between pages. I also utilized an .active class in the CSS to visually highlight the current page in the navigation bar.

2. Modern Flexbox Layout
I utilized CSS Flexbox to manage the global layout:

Sticky Footer: By setting the body to display: flex with a min-height: 100vh, I ensured the footer always stays at the bottom of the viewport on short pages, but is pushed down naturally on pages with more content.

Main Growth: The main element uses flex: 1 to occupy all available vertical space, preventing the footer from floating in the middle of the screen.

3. Component Styling
Section Cards: Each section uses height: fit-content and align-items: flex-start to ensure that content containers only take up the space they need, preventing unnecessary vertical stretching.

Skill Tags: Proficiency items are styled as modern pill-shaped tags using background colors and rounded borders.

Global Consistency: A single style.css file manages the design of all three pages, ensuring a uniform look and feel regarding typography, colors, and spacing.