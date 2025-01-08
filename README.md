# Quick React Dev Setup

Create a minimal React development environment using Vite.

## Quick Start

```bash
# Create project
npm create vite@latest my-app -- --template react-ts

# Install dependencies
cd my-app
npm install

# Start development server
npm run dev
```

Visit `http://localhost:5173` in your browser.

## Project Structure

```
my-app/
├── src/
│   ├── App.tsx       # Main component
│   └── main.tsx      # Entry point
├── index.html        # HTML template
├── package.json      # Dependencies
└── vite.config.ts    # Vite configuration
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

