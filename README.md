# Calculus Flashcards

Flashcards for the parts of CalculusI that are required to be memorized to have success in the class.

## Two versions of the app
  * SECTIONED
    * Only questions in a particular section are offered. Use "Grab Bag" to offer questions from all sections.
    * https://realityexpander.github.io/Flashcards/sectioned.html
  * LINEAR
    * All questions are randomly offered.
    * Benefit: The question object array is much simpler than the sectioned version.
    * https://realityexpander.github.io/Flashcards/linear.html  
   
### Conversation that generated the App
  * https://share.gemini.google/X0NRzjit0m43 (public link)
  * https://gemini.google.com/app/c584261d84ab7c09 (private link)

# Calculus I Mastery Flashcards

## Overview
The **Calculus I Mastery Flashcards** app is a lightweight, interactive, single-page web application designed to help students memorize the fundamental formulas, identities, and rules required for a standard Calculus I course. It serves as an excellent study companion for quick, repetitive practice without the need for physical flashcards.

## Features
* **Topic Filtering:** Study exactly what you need by selecting from five distinct mathematical categories, or challenge yourself with a mix of everything.
* **Beautiful Math Rendering:** Integrates the KaTeX library to display complex mathematical notation (like limits, integrals, and fractions) cleanly and accurately.
* **Dynamic Randomization:** The app continuously randomizes both the question order and the placement of the multiple-choice options, preventing positional memorization and keeping the study session fresh.
* **Instant Visual Feedback:** Selecting an answer immediately highlights the correct and incorrect choices using intuitive color coding (green for correct, red for incorrect).
* **Progress Tracking:** Displays your current study section and keeps track of how many cards are available in the selected category.

## Study Categories
The flashcards are divided into the following sections, aligning with standard Calculus I curricula (such as Larson's Calculus):

1. **Trigonometry & Precalculus Essentials:** Unit circle values and fundamental identities (Pythagorean, reciprocal, quotient).
2. **Limits & Definitions:** The limit definition of the derivative and special trigonometric limits.
3. **Derivative Rules:** Power, product, quotient, and chain rules, alongside derivatives for trigonometric, exponential, logarithmic, and inverse trig functions.
4. **Integration & Antiderivatives:** The Fundamental Theorem of Calculus and basic indefinite integrals.
5. **Geometry Formulas for Applications:** Area, volume, and surface area formulas necessary for related rates and optimization problems.
6. **Grab Bag:** A randomized mix of all the above categories for comprehensive review.

## How to Use
Because this is a standalone HTML file, there are no installations, dependencies, or build steps required.

1. Download or save the application file (e.g., `calculus_flashcards.html`).
2. Double-click the file to open it in any modern web browser (Chrome, Safari, Firefox, Edge).
3. Select your desired study topic from the top menu.
4. Read the formula prompt and click the button corresponding to the correct answer.
5. Click **Next Formula** to proceed to a newly randomized card.

## Technical Stack
* **HTML5 / CSS3:** For structuring and styling the responsive user interface.
* **Vanilla JavaScript (ES6):** Handles the application logic, array shuffling, state management, and user interactions.
* **KaTeX:** A fast, lightweight JavaScript library used via CDN for TeX math rendering.
