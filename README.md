# NARUTO 25th Anniversary Tribute

An interactive React + Vite experience celebrating Naruto's 25th anniversary with animated components and smooth scrolling.

## Features

- **Hero Section** - Immersive landing with animated visuals
- **Swing Animation** - Frame-by-frame character animation
- **Sage Mode** - Interactive transformation sequence
- **Bonds** - Character relationship showcase
- **Custom Cursor** - Branded cursor interaction
- **Preloader** - Smooth entry experience
- **Lenis Smooth Scroll** - Buttery scroll performance

## Tech Stack

- React 18 + Vite
- Lenis for smooth scrolling
- Custom ReactBits components (SplitText, ScrollVelocity, Noise, Lightning, ClickSpark)

## Getting Started

```bash
npm install
npm run dev
```

Open `http://localhost:5173` in your browser.

## Build for Production

```bash
npm run build
```

Output in `dist/` folder.

## Project Structure

```
src/
├── components/     # UI components (Hero, Swing, SageMode, Bonds, Cursor, Preloader)
├── reactbits/      # Reusable animation primitives
├── lib/            # Hooks & utilities
├── App.jsx         # Main app composition
└── main.jsx        # Entry point
```