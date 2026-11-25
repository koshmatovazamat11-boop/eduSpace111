# EduSpace — learning platform prototype

A responsive front-end prototype for a student learning platform. The interface combines an editorial visual style, lavender accents, course discovery, personal learning tools and lightweight gamification.

## Features
- Responsive dashboard and navigation
- Course catalogue with search, category and level filters
- Course detail pages with lesson lists
- Demo lesson completion and quiz interactions
- XP, levels, progress and achievements
- Notes with create/search/delete
- Task planner and 25-minute focus timer
- Demo profile and light/dark theme
- Local persistence using `localStorage`

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. For a local development server, use the VS Code Live Server extension.

No build step is required.

## Important project status
This is a front-end prototype. The demo profile is **not real authentication**. Data is stored in the current browser using `localStorage`, so it does not sync across devices. Course content and quiz examples are demonstration content. Do not use this version to store sensitive personal information.

## Suggested production roadmap
1. Add Firebase Authentication or another secure authentication provider.
2. Store users, courses, lessons, notes and progress in a database with access rules.
3. Build an admin/instructor panel and content moderation workflow.
4. Add real video hosting, graded quizzes and certificate verification.
5. Add automated tests, accessibility checks and user testing.

## Deploy with GitHub Pages
1. Create a public GitHub repository.
2. Upload `index.html`, `style.css`, `app.js`, and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, branch `main`, folder `/ (root)`, then save.
5. Wait for deployment and open the published URL on desktop or mobile.

## Accessibility and UX notes
The prototype includes semantic landmarks, labels for key controls, keyboard-operable course cards, visible focus behavior from browser defaults, responsive layouts and reduced-motion support. Before production, test with keyboard-only navigation, screen readers and real students.
