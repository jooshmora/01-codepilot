# Copilot Instructions for AI Coding Agents

## Project Overview
This is a minimal web project consisting of three main files:
- `index.html`: The main HTML file for the web page.
- `style.css`: Contains all CSS styles for the page.
- `README.md`: Basic project information and setup notes.

## Architecture & Patterns
- The project is a static website. There is no JavaScript, backend, or build system.
- All logic and structure are contained in the HTML and CSS files.
- The HTML file is the entry point; CSS is linked via `<link rel="stylesheet" href="style.css">`.
- No frameworks or external dependencies are present.

## Developer Workflows
- No build or test commands are required. Simply open `index.html` in a browser to view changes.
- For live preview, use VS Code's Live Server extension or similar tools.
- All changes are made directly to the HTML and CSS files.

## Project-Specific Conventions
- Keep HTML semantic and minimal. Use standard tags (`<header>`, `<main>`, `<footer>`, etc.) where possible.
- Place all styles in `style.css`; do not use inline styles or `<style>` tags in HTML.
- No custom scripts or automation are present or expected.

## Integration Points
- No external APIs, libraries, or services are integrated.
- No cross-component communication is needed.

## Example Patterns
- To add a new section, create a semantic HTML element in `index.html` and style it in `style.css`.
- To update the look and feel, modify `style.css` only.

## Key Files
- `index.html`: Main structure and content.
- `style.css`: All styling rules.
- `README.md`: Project purpose and setup.

## How to Be Productive
- Focus on clear, semantic HTML and organized CSS.
- Preview changes in a browser for immediate feedback.
- No need to set up or run any build tools.

---
_If you need to add new features, follow the existing minimal and semantic approach. Ask for clarification if requirements are unclear or if you encounter non-standard patterns._
