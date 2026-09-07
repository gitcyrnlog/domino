# G6 Domino Rankings

A live leaderboard for tracking domino game results with real-time sync across devices using Firebase.

## Features

- 📊 Live rankings sorted by sap ratio (given/received)
- 🎯 Quick game logging with winner/loser selection  
- 🔐 Admin panel to edit player stats and reset data
- ☁️ Real-time sync across all devices via Firebase
- 💾 Local storage fallback if Firebase is unavailable

## How It Works

- Data is stored in Firebase Realtime Database under `leaderboard` path
- Changes on any device sync instantly to all others
- Browser localStorage serves as backup if Firebase is unavailable
- Admin password: `G62026`

## Usage

- **Log Game**: Click "+ Record game" to add a winner and loser
- **Edit Stats**: Click "Admin access" and enter password to manually adjust player data
- **Reset**: Clear all data with "Reset defaults" button in admin panel

## Players

- Benti, Chris, Geo, Hasani, Burley, Juson, Javari, Leshaun, Mito