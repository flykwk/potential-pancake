---
name: frontend-ui-design
description: Design and implement polished, responsive front-end interfaces. Use when creating or improving web pages, app screens, components, or visual prototypes.
---

# Front-end UI design

## Goal

Create interfaces that are clear, distinctive, accessible, and usable—not generic layouts.

## Process

1. Inspect the existing project before changing code.
   - Identify the framework, styling approach, component library, and existing design conventions.
   - Reuse existing components and tokens when appropriate.
   - Avoid replacing project configuration or dependencies unless necessary.

2. Understand the screen’s purpose.
   - Identify the primary user, their main task, and the most important action.
   - If the brief is ambiguous, make reasonable assumptions and state them briefly.
   - Keep the interface focused on the user's task.

3. Choose a visual direction before coding.
   - Define the mood, typography, color palette, spacing rhythm, and layout.
   - Make choices that fit the product and audience.
   - Avoid defaulting to generic gradients, identical card grids, or decorative effects without a purpose.
   - Use the project’s existing visual language if one is established.

4. Design the full experience.
   - Include relevant loading, empty, error, success, and disabled states.
   - Make navigation and calls to action clear.
   - Use concise, plain-language labels that describe what actions do.

5. Implement responsively.
   - Support narrow and wide screens.
   - Use semantic HTML and existing project patterns.
   - Make interactive controls usable by keyboard and touch.
   - Respect reduced-motion preferences if adding animation.

6. Check the result.
   - Run the available lint, type-check, and test commands when practical.
   - Review the page at mobile and desktop sizes.
   - Look for overflow, weak contrast, inconsistent spacing, unclear hierarchy, and broken interactions.
   - Fix issues you find before finishing.

## Design principles

- Establish a clear visual hierarchy: users should quickly see what matters and what to do next.
- Use consistent spacing, typography, colors, and component behavior.
- Prefer purposeful detail over decoration.
- Keep text readable and interface copy specific.
- Provide visible focus states and accessible names for controls.
- Do not invent product behavior that the brief or existing code does not support.

## Response

When finished, summarize:
- What you changed
- Any assumptions you made
- Checks you ran and anything that remains incomplete
