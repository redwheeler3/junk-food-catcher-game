# Junk Food Catcher Game

An arcade-style browser game built with React, TypeScript, Vite, and Tailwind CSS.

The goal is simple: catch the good junk food, avoid the veggies, and survive as long as you can.

## Play Online

Live site: [https://junk.jeffo.net](https://junk.jeffo.net)

## How to Play

- Catch **🍔 burgers** for **+5 points**
- Catch other **junk food** like **🍕** for **+1 point**
- Avoid **veggies** like **🥦** or lose **3 points**
- Catch **⚡ power-ups** for temporary speed and invincibility
- Missing too many good items ends the game

### Controls

- **Keyboard:** `←` / `→` or `A` / `D`
- **Touch devices:** tap or drag on the game area

## Features

- Fast arcade gameplay
- Keyboard and touch controls
- Score tracking with local high score storage
- Power-up mechanic
- Sound effects and background music
- Responsive single-page app deployment

## Tech Stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui components
- React Router
- TanStack Query

## Getting Started

### Prerequisites

- Node.js
- npm

### Install

```sh
npm install
```

### Start the development server

```sh
npm run dev
```

### Build for production

```sh
npm run build
```

### Preview the production build

```sh
npm run preview
```

## Available Scripts

- `npm run dev` — start the Vite dev server
- `npm run build` — create a production build
- `npm run build:dev` — build using development mode
- `npm run preview` — preview the production build locally
- `npm run lint` — run ESLint
- `npm run deploy` — build and publish `dist` with `gh-pages`

## Project Structure

```text
src/
  components/
    Game.tsx
  pages/
    Index.tsx
    NotFound.tsx
  lib/
  hooks/
  test/
```

## Deployment Notes

This project is configured for static deployment with `gh-pages` and uses the custom domain:

- `https://junk.jeffo.net`

The CNAME is stored in:

```text
public/CNAME
```

## License

This project is licensed under the [MIT License](./LICENSE).
