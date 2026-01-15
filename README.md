# CSP451 Web Starter — Week 2 Checkpoint 2

This repository is a **starter template** for practicing:
- Git branching strategies (GitHub Flow / Git Flow-lite)
- Pull Requests + review workflow
- Intentional merge conflicts + manual resolution
- Clean history using **Squash and merge**

## Quick Start

```bash
npm install
npm run dev
```

Open: http://localhost:3000

## Structure

- `src/app.js` — Express server entry
- `src/routes/` — route modules
- `src/controllers/` — controller functions
- `src/services/` — reusable services (auth helpers, etc.)
- `src/db/` — database module (starts as a stub)
- `public/` — static UI (includes `/login`)
- `docs/` — reports + screenshots checklist

## Required Branches
Create these branches exactly:
- `feature/user-authentication`
- `feature/database-connection`
- `feature/api-endpoints`

## Suggested Conflict Targets
To intentionally create a merge conflict, edit the same lines in one of:
- `README.md`
- `src/app.js`
- `src/routes/api.js`

## How to Run Tests (lightweight)
```bash
npm test
npm run lint

```

## User Authentication Features

This feature will improve the login experience by focusing on the client-side validation for better user feedback.

## Features

- Username and Password is mandatory requirement
- Without this, an error message will show when the fields are empty
- Username and Password is requirement for necessary requirements

The main logicl for this is to prevent unnecessary API calls and provide fast feedback to users that not follow this feature.
