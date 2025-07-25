# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple static website hosted on GitHub Pages, consisting of basic HTML and CSS files. The site serves as a personal portfolio/learning project.

## Architecture

- **index.html**: Main HTML file with semantic structure (header, nav, main sections for about/projects/contact, footer)
- **style.css**: Responsive stylesheet using flexbox layout, CSS gradients, and mobile-first design

## Development Workflow

Since this is a static site deployed via GitHub Pages:

1. Make changes to HTML/CSS files locally
2. Test by opening `index.html` in a browser
3. Commit and push changes to the `main` branch
4. GitHub Pages automatically deploys from root of `main` branch
5. Live site: `https://r32t.github.io/WebsiteTester/`

## Key Details

- No build process or package manager required
- Deployment is automatic on push to main
- CSS uses purple gradient theme (#667eea to #764ba2)
- Mobile responsive via CSS media queries at 768px breakpoint


7 Claude rules
1. First think through the problem, read the codebase for relevant files, and write a plan to tasks/todo.md.
2. The plan should have a list of todo items that you can check off as you complete them
3. Before you begin working, check in with me and I will verify the plan.
4. Then, begin working on the todo items, marking them as complete as you go.
5. Please every step of the way just give me a high level explanation of what changes you made
6. Make every task and code change you do as simple as possible. We want to avoid making any massive or complex changes. Every change should impact as little code as possible. Everything is about simplicity.
7. Finally, add a review section to the [todo.md](http://todo.md/) file with a summary of the changes you made and any other relevant information.
