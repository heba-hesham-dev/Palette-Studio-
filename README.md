# Palette-Studio

A web tool that helps designers and developers turn a set of colors into an organized, accessible palette with ready-to-use code.

## The problem

Many people building a website or app have colors in mind, but they do not know where each color should go, or whether the text will be readable on its background. They end up checking contrast in several tools and writing color code by hand.

## What Palette Studio does

1. Enter your colors.
2. Get a suggested role for each color: Primary, Secondary, Background, Text, and Accent.
3. Check every color pair against WCAG contrast rules (AA and AAA).
4. Get the nearest accessible shade when a pair fails.
5. Preview the palette as people with different types of color blindness see it.
6. Export the palette as CSS variables, a Tailwind config, or JSON design tokens.

Everything runs in the browser. No account, no server, no personal data.

## Planned features

- Palette suggestions based on project type (Food, Health, Finance, Education, Kids) and mood (Calm, Energetic, Professional)
- Live UI preview: see the palette applied to sample buttons, cards and forms
- Light and dark mode palettes
- Save and share a palette with a link

## Tech stack

- JavaScript
- React + Vite
- CSS
- Vitest for unit tests of the color calculations

## Status

Early development.

## Author

Heba Hesham
UI/UX Designer and Software Developer
