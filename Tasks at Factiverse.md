# Tasks at Factiverse

## Product & Prototyping

### 2023-2026 Factiverse App

Goal: Re-design of _AI Editor_ focusing on UX/UI and integrating all Factiverse features into one app.\
Feature Overview: Fact-checking of text and video, YouTube channel monitoring, FactiSearch dashboard, API access.\
Tech Stack: Based on _React Template_, Azure, Vite, Cursor, Storybook, Playwright\
Team size: 4\
User signups: ~6000

### 2022-2024 FactiSearch

Goal: Dashboard to **explore articles** from fact-check websites worldwide.\
Feature Overview: Feed with recent fact-checks, searchable with various queries and filters.\
Tech Stack: Based on _React Template_\
Team size: 2

### 2021-2023 AI Editor

Goal: Re-design of the _Intelligent Text Editor_ prototype as a demo for potential customers.\
Feature Overview: A text editor with built-in fact-checking functionality.\
Tech Stack: Based on _React Template_\
Team size: 2\
User signups: ~1000

### 2021-2023 Microfacts

Goal: Add short explainers to named entities in articles.\
Feature Overview: Scan any text for named entities and show a explainer popup for each.\
Tech Stack: Based on _React Template_\
Team size: 2

### 2021-2025 React Template

Goal: Establish a shared frontend foundation for all Factiverse products — standardising tooling, enforcing code quality, and reducing setup time for new apps.\
Feature overview: **Simple instructions and setup** to get started with a new React app.\
Tech stack: React, Webpack, Jest, Eslint, Typescript, Material UI, Emotion, Github Pages, i18next

### 2021 Intelligent Text Editor

Goal: Front-end prototype to **visualize Factiverse API** capabilities for potential investors.\
Feature overview: fact-check both single factual claims and claim detection in longer texts.\
Tech stack: HTML, Javascript, CSS

## Frontend Architecture

### React Environment
Problem: The first prototype in plain HTML/CSS/JS was slow to develop, hard to debug, difficult to test and didn't scale to multiple products.
Approach: Built a shared React environment with tools chosen to address each pain point: React for structure and reusability, Material UI to skip rebuilding common components, ESLint for consistency, Jest and Playwright for user-centric testing, Sentry for production error visibility.

### Design System
Problem: No shared component library made it hard to collaborate with the UX designer, keep UI consistent, and reuse work across products.
Approach: Introduced Storybook to develop components in isolation, document them, enable visual regression testing with Chromatic, and keep components presentational and discoverable.

## Third-party Integrations

## Quality & UX

## Team & Cross-functional

- **Agentic coding workflows** and rules to speed up development while ensuring quality and consistence
- **Github best practices** (branches with Git flow, branch protection, issue labels, issue/PR templates, consistent commit messages)
- **User-centered testing** with Jest, React Testing Library, user-event, code coverage reports
- **Authentication and sign-up forms** with Auth0
- **Stripe** integration for payments
- **Customer.io** integration for email campaigns
- **Sentry.io** integration for error logging
- **Conducted job interviews** with potential front-end hires
- Ensure **accessibility**
- Design **user tutorials**
- Design logos, business cards
- Machine-embroider branded keychains
- Research example texts for fact checking
- Write **documentation**
