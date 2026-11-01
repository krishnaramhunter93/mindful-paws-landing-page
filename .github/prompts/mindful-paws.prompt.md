---
name: "Build Mindful Paws Landing Page"
description: "Create a polished, self-contained landing page for the Mindful Paws pet grooming salon."
argument-hint: "Optionally specify a different output filename or visual direction."
agent: "agent"
---

Build a complete, polished landing page for the boutique pet grooming salon Mindful Paws. Use the existing workspace conventions if relevant; otherwise make the page self-contained with no frameworks, external dependencies, or build step.

## Context

This is a single-page website for a calm, premium pet grooming salon. It should feel welcoming, thoughtful, and easy to use on both mobile and desktop.

## Instruction

Create a single HTML file named `mindful_paws.html` in the workspace root (or use a different filename if the user requests one). Include all CSS and JavaScript in the file. Make the page responsive, accessible, and fully functional.

Include:
- A hero section with the business name **Mindful Paws** and tagline **“Where grooming meets calm”**, plus a clear booking call to action.
- An interactive booking quiz that asks one question at a time: pet type (Dog, Cat, Other), size (Small, Medium, Large), then service (Bath & Brush, Full Groom, Spa Day). Show a price estimate after the selections, with a way to go back or change answers. Treat estimates as starting prices and make any size or pet price adjustments clear.
- A services section with four service descriptions and prices.
- A happy-pets gallery using self-contained visual placeholders; do not rely on remote images.
- A booking form with pet name, owner name, phone number, and preferred date. Validate required fields and clearly explain that submitting requests an appointment rather than confirming one. Do not imply that form data is sent to a server when no backend exists.

Use semantic HTML, keyboard-accessible controls, visible focus states, and reduced-motion support. Keep the visual design cohesive and refined, with warm natural colors, considered typography, generous spacing, and smooth but restrained transitions.

## Input

- Business: Mindful Paws
- Tagline: “Where grooming meets calm”
- Services and starting prices:
  - Bath & Brush — $45
  - Full Groom — $75
  - Spa Day — $120
  - Puppy's First Groom — $55
- Quiz services: Bath & Brush, Full Groom, Spa Day
- Pet types: Dog, Cat, Other
- Sizes: Small, Medium, Large

## Output

Save the finished page as `mindful_paws.html` in the workspace root unless the user specifies another filename. Return a concise summary of the page and any verification performed.
