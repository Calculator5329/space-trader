# Space Trader

A space trading game built with Phaser 3 and React, inspired by the classic game Gazillionaire. Manage resources, trade goods, and navigate between planets.

## What It Is

A strategy trading game where players pilot a spaceship, buy and sell goods at different planets, and manage limited resources like credits and fuel. The game features dynamic pricing across planets, inventory management, and strategic trading decisions to maximize profit.

## Tech Stack

- **Game Engine**: Phaser 3
- **Frontend**: React 19 + TypeScript
- **Build**: Vite with Turbopack
- **Styling**: Tailwind CSS
- **Charts**: React Plotly.js, Recharts
- **Routing**: React Router DOM
- **UI Components**: Headless UI, react-icons
- **Animations**: Framer Motion

## Getting Started

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn

### Installation

```bash
cd my-game
npm install
```

### Development

```bash
npm run dev
```

The game will be available at `http://localhost:5173`

### Building for Production

```bash
npm run build
```

## Game Features

- **Space Navigation**: Fly your ship between planets using arrow keys
- **Trading System**: Buy and sell goods with dynamic prices across planets
- **Resource Management**: Manage credits, fuel, and inventory
- **Planet Exploration**: Visit different planets with unique specialties
- **Dynamic Economy**: Prices fluctuate between planets based on supply and demand

## Game Mechanics

- **Credits**: Your currency for buying goods
- **Fuel**: Required for space travel (consumed when moving between planets)
- **Inventory**: Goods you carry and trade
- **Planets**: Each has unique specialties and trade goods

## Controls

- **Arrow Keys**: Move your ship in space
- **Mouse Click**: Interact with planets and UI buttons
- **Trading Interface**: Buy/sell goods when docked at planets

## Project Structure

```
my-game/
├── src/
│   ├── game/
│   │   ├── Game.ts           # Main game configuration
│   │   ├── GameState.ts      # Game state management
│   │   └── scenes/           # Game scenes
│   ├── App.tsx               # React wrapper
│   └── main.tsx              # Entry point
├── public/assets/            # Game sprites
└── package.json              # Dependencies
```

## Game Assets

Currently uses placeholder graphics. To add custom assets, place them in `public/assets/`:
- `ship.png` - Player spaceship
- `planet.png` - Planet graphics
- `space-background.png` - Space background
- `trading-background.png` - Trading UI
- `planet-background.png` - Planet surface
- `game-logo.png` - Main menu logo

## Development Notes

- Phaser 3 handles game logic and rendering
- React manages UI and state
- TypeScript provides type safety
- Vite handles fast development and production builds
