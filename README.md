# Next.js Boilerplate

[![ci](https://github.com/rodolfoafl/nextjs-boilerplate/actions/workflows/ci.yml/badge.svg)](https://github.com/rodolfoafl/nextjs-boilerplate/actions)

An opinionated **Next.js + TypeScript** starter, ready for real-world projects: testing, component documentation, code quality automation and CI configured out of the box.

## Why this boilerplate?

Starting a new project usually means spending the first day wiring up linting, testing, hooks and CI. This template skips that day. Clone it, run one command, and start building features with quality gates already in place.

## What's inside

**Core**
- [Next.js](https://nextjs.org/) with [TypeScript](https://www.typescriptlang.org/)
- [Styled Components](https://styled-components.com/)

**Testing**
- [Jest](https://jestjs.io/) + [React Testing Library](https://testing-library.com/docs/react-testing-library/intro)

**Component workflow**
- [Storybook](https://storybook.js.org/) for isolated component development and documentation
- Component generator (Plop) — scaffold a new component with its test, story and styles in one command

**Code quality**
- [ESLint](https://eslint.org/) + [Prettier](https://prettier.io/) with shared editor settings (`.editorconfig`, `.vscode`)
- [Husky](https://github.com/typicode/husky) + lint-staged — lint and test staged files on every commit
- CI pipeline with GitHub Actions running lint, tests and build on every push

## Getting started

```bash
# use this template (GitHub "Use this template" button) or clone it
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to see the app.

## Commands

| Command | Description |
| --- | --- |
| `dev` | runs the app at `localhost:3000` |
| `build` | creates the production build |
| `start` | serves the production build |
| `lint` | runs ESLint on all components and pages |
| `test` | runs the full Jest test suite |
| `test:watch` | runs Jest in watch mode |
| `generate ComponentName` | scaffolds a new component (files, test, story) |
| `storybook` | runs Storybook at `localhost:6006` |
| `build-storybook` | builds the static Storybook |
