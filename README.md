# TikTok-Style Book Reader

A minimal, high-performance web-based book reader designed with a vertical, swipe-based experience similar to TikTok. This application is optimized for mobile devices and provides an immersive reading experience for book summaries.

## Core Features

- **TikTok-Style Scrolling**: Vertical scroll-snap navigation between pages.
- **Smart Parsing**: Automatically splits chapters and pages using special Markdown delimiters (`---` for chapters, `>>` for pages).
- **Interactive Quizzes**: Dynamic quiz pages generated directly from Markdown (using `+` for questions and `-0-`/`--` for options).
- **Smooth Animations**: Glassmorphism UI with subtle micro-animations and a "heart burst" favorite system.
- **Dark Mode**: Premium OLED-ready dark theme by default.
- **Offline Ready**: Configured for PWA (Progressive Web App) support.

## Project Structure

- `index.html`: The main landing page/library.
- `reader.html`: The core reading engine.
- `style.css`: Modern design system and layout.
- `books.json`: Registry for available book summaries.
- `books/`: Directory containing the book content.
  - **Note**: The `.md` files in this directory (e.g., `psyco1.md`) are provided as **examples** of the structured format required by the engine.

## Development Note

This project was entirely **vibecoded** — developed through an iterative AI-assisted pair programming process to prioritize speed, aesthetics, and fluid user experience.

---

*Built with passion for better reading habits.*
