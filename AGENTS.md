# AGENTS.md

# AI Agent Guide for Pedro's Portfolio Repository

## Project Overview

- **Name:** Personal Portfolio Website
- **Description:** A professional, fast-loading, and visually appealing portfolio website to showcase projects, skills, and experience. It is deployed and served directly via GitHub Pages.
- **Mission Statement:** To maintain and enhance a high-performance, elegant, and accessible online presence that accurately reflects professional growth and technical capabilities.

## Technology Stack

- **Core:** Static HTML5, modern CSS (Bootstrap), and vanilla JavaScript.
- **Deployment:** GitHub Pages.
- **Build Tools:** None (static site).
- **CV System:** LaTeX, using a custom template based on the "Rover Resume" template.

## Project Structure & Conventions

- **Root Directory:** Contains the main [`index.html`](index.html), [`favicon.ico`](favicon.ico), and configuration files.
- **`assets/` Directory:** Houses all static assets, including [`css/`](css/), [`js/`](js/), and [`images/`](images/).
- **`CV/` Directory:** Dedicated to resume and CV management. This folder contains `.tex` source files and compiled PDFs. The core file is [`resume.tex`](CV/resume.tex).
- **Git Workflow:** Adhere to a clear commit message convention (e.g., Conventional Commits). The primary branch is `main`. All development should occur on feature branches and be merged via pull requests for significant changes.

## AI Directives and Responsibilities

- **Primary Goal:** Assist in the development, debugging, and enhancement of the portfolio site. Ensure all changes align with the project's mission.
- **Code Quality:** Write clean, semantic, and accessible HTML5. Prioritize performance and SEO best practices. Ensure CSS and JS are well-organized and commented.
- **CV Management Task:** The principal future objective is to implement a robust CV versioning system. This involves creating a GitHub Action workflow that automatically detects changes to `.tex` files within the `CV/` directory, compiles `resume.tex` into a `CV.pdf`, and commits the resulting PDF back to the repository.
- **Autonomy:** You are expected to proactively suggest improvements for code structure, performance, user experience, and the implementation of the CV workflow. You can create new files, refactor existing code, and update documentation as needed, always providing a clear summary of your actions.

## Future Roadmap

1.  Implement the automated LaTeX compilation pipeline using GitHub Actions for seamless CV updates.
2.  Explore the possibility of hosting multiple CV versions or formats (e.g., a one-page vs. a detailed version).
3.  Continuously optimize the website for Core Web Vitals and accessibility scores.