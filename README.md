# Urami N5 Kanji

An ultra-premium, interactive Single Page Application (SPA) designed to help you study JLPT N5 Kanji with style. 

## Features

- **Smart Categorization**: 113 N5 kanji are dynamically grouped into logical categories (e.g., "Numbers & Currency", "Time & Calendar", "Actions & Verbs") for intuitive browsing and studying.
- **Asymmetric Glassmorphism UI**: Uses a breathtaking "Dark Zen" aesthetic featuring thick frosted glass panels, glowing typography, and micro-animations.
- **Fluid & Responsive Dashboard**: Clicking any kanji opens an incredibly sleek, fluid dashboard popup overlay that automatically scales to perfectly fit any screen size—built entirely with modern, responsive Vanilla CSS (using `clamp()`, `minmax()`, and flexbox) without the bloat of external libraries like Tailwind.
- **Detailed Kanji Data**: Instantly view the Kanji, Romaji, Meaning, Onyomi, Kunyomi, and common vocabulary words without ever leaving the page.

## Tech Stack

- **HTML5**: Semantic and minimal.
- **Vanilla CSS3**: Advanced CSS properties including `backdrop-filter`, `clamp()`, CSS Grid, Flexbox, and CSS Variables.
- **Vanilla JavaScript**: Dynamic DOM manipulation and event delegation for the modal and categorization logic. No frameworks or external dependencies.

## Usage

Simply open `index.html` in any modern web browser to start studying! No build steps or servers required.

## Structure

- `index.html`: The main entry point containing the dynamic categorization script and the asymmetric modal layout.
- `style.css`: The massive, fully responsive styling file responsible for the Dark Zen aesthetic and fluid typography.
- `data.js`: The central data store containing the dictionary of all 113 N5 Kanji.
- `premium_bg.png`: The stunning AI-generated background image.
