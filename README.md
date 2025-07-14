# PLL_Dashboard

**PLL Dashboard for Comparing Lacrosse Players**

This interactive React.js dashboard allows users to compare Premier Lacrosse League (PLL) players based on performance metrics. Users can visualize and evaluate how individual components (goals, assists, turnovers, ground balls, etc.) contribute to a player's overall rank and DSA Impact Factor.

## Features

- Load and parse player data from CSV
- Filter by position, team, or name
- Select multiple players for side-by-side comparison
- Bar and radar charts for stat visualization
- Tooltips showing player rank and DSA score
- Auto-loads top 10 players on initial launch

## Built With

- React.js
- TailwindCSS
- Recharts
- PapaParse

## How to Run

1. Clone the repository
2. Make sure you have a static server (`serve`, `http-server`, or just use Vite/Next if wrapped)
3. Drop the project into the server root and open in a browser

## Data

The dashboard consumes a CSV file formatted with individual player stats including:
- DSA Impact Factor
- Goals, Assists, Shots
- Turnovers, Ground Balls, Faceoffs, etc.

## License

MIT
