# AGENTS.md
## Project Overview

This repository contains the source code for Luke Squire’s personal portfolio website.

The site is a lightweight static website deployed via GitHub Pages.

Primary goals of the site:

- Present Luke’s professional experience
- Show a visual career blueprint
- Provide ways for recruiters or collaborators to contact him

## Tech Stack

This site intentionally uses a simple stack.

Languages and tools:
- HTML
- CSS
- Static assets (images, SVGs)
- GitHub Pages deployment

There are no frameworks, build tools, or package managers.

Do not introduce:
- React
- Tailwind
- Bootstrap
- Node build systems
- CSS frameworks
- JavaScript frameworks

The goal is to keep the project simple, portable, and maintainable.

## Development Workflow

Local development should be done using VS Code with Live Server.

Typical workflow:
1. Edit HTML or CSS
2. Preview changes locally with Live Server
3. Validate layout and responsiveness
4. Commit changes
5. Push to GitHub
6. GitHub Pages deploys automatically

AI agents should assume that local preview exists and deployment is automatic.

## Design Philosophy

The site follows a clean, executive product-leader aesthetic.

Design principles:
- minimalist
- structured layouts
- strong typography
- subtle visual hierarchy
- calm professional tone

Avoid:
- flashy UI
- gradients
- heavy animations
- overly decorative visuals
- complex UI components

This site should feel like a modern tech executive portfolio.

## Visual Style

Primary accent color:
#0F766E

Background:
light neutral gray

Typography:
system sans-serif fonts

Spacing should use the spacing variables defined in the :root section of styles.css.

## Layout Rules

Pages use a centered container layout.

.container
max-width: 1040px

Content sections should follow this pattern:

<section> <div class="container">

Maintain consistent vertical spacing between sections.

Do not introduce drastically different layout patterns without reason.

## Mobile Responsiveness

The site uses mobile-first design.

Primary breakpoints in styles.css:
- 960px
- 900px
- 640px

Expected responsive behavior:

- grids collapse to vertical stacks
- hero sections scale typography
- navigation remains readable
- images scale to container width

## Editing Guidelines for AI Agents

When modifying the site:
- Prefer simple HTML and CSS edits.
- Follow the existing style system defined in styles.css.
- Avoid introducing new dependencies.
- Do not restructure the project unless necessary.

Keep edits consistent with the existing design system.

## File Responsibilities

index.html
Homepage content and career overview.

about.html
Personal background and philosophy.

lets-build.html
Contact page.

styles.css
Global styles and responsive layout rules.

assets/
Images and static media.

## Commit Style

Commit messages should be short and descriptive.

Examples:

- Improve about page layout
- Fix mobile spacing
- Add profile photo
- Adjust hero typography
- Refine CTA button styling