# mines-simulator

A small Vite + React app containing the Mines Simulator (5×5 grid).

## Usage

1. Unzip the project
2. `npm install`
3. `npm run dev`
4. Open `http://localhost:5173` (Vite default)

To deploy: push to GitHub and connect to Vercel or Netlify (or upload build to any static host).

The app supports:
- Clicking tiles to mark revealed safe (💎) or bomb (💣)
- Coordinate labels A1–E5
- Import/export board state as JSON
- Generate Base64 share link `?s=...` which auto-loads on app open
