# AGENTS.md

## Project overview

This is a mobile-first workout tracking web app built with Next.js, TypeScript, Tailwind CSS, Supabase, and Recharts.

## Product priorities

1. Fast workout logging on mobile
2. Clean, reliable data model
3. Strong TypeScript safety
4. Easy-to-read UI in dark mode
5. Maintainable component structure

## Engineering rules

* Prefer simple, maintainable solutions over clever ones
* Reuse components where practical
* Keep forms validated with Zod
* Use consistent naming
* Avoid unnecessary dependencies
* Keep business logic separate from presentation where possible
* Make mobile UX a first-class priority

## UI rules

* Mobile first
* Large tap targets
* Dark mode friendly
* Card-based layout
* Clean spacing
* Avoid clutter
* Prioritize speed of interaction on the active workout screen

## Data rules

* Workout session history must remain stable even if plans change later
* Weekly volume must be calculated from completed sessions
* Only one workout plan may be active at a time
* Bodyweight entries are date-based
* Previous workout values should be available during current workout logging

## Code generation expectations

When adding features:

* update types
* update validation
* update seed data if needed
* update README if setup changes
* keep the app runnable

## Before finishing

Always verify:

* pages render
* types compile
* forms validate
* key workout flows are usable
* mobile layout remains readable
