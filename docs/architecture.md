# Architecture

The coding agent must follow this document. You own it: review every change to it, and commit changes to this file separately from code changes.

## Stack (fixed)

- React Router 8, framework mode
- JavaScript, not TypeScript
- SQLite through `better-sqlite3`

(Additional modules must be added here before they are used.)

## Rendering: SSR or SPA

**Decision:** TODO

**Why, for this app:** TODO, in a few sentences about *your* app rather than SSR vs SPA in general.

## Structure

TODO: Generate this from `reference/`, then review it and correct it for your decision above. Name the folders and what goes in each one, where database code lives, and where login and permission checks happen.

## Conventions

TODO: Generate these from `reference/`, then review them. Each one must be a rule that someone can check, not a description. "All SQL lives in `db.js`" is a rule. "Uses a modular structure" is not.

- Data access:
- Login, sessions and permissions:
- Validation and errors:
- Loading states and optimistic updates:
- Styling:
- Testing:
