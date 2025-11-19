# Catch 41 - Dart Practice App 🎯

A web-based dart practice application for improving your checkout skills on outs 61-100. Perfect your finishing ability with this interactive training tool used by dart players worldwide.

## Features

- **Practice Mode**: Complete all outs from 61 to 100
- **Two-Player Support**: Compete with a friend in alternating turn mode
- **Smart Recommendations**: Get optimal takeout suggestions for each out
- **Score Tracking**: Points awarded based on darts used (2 darts = 3 points, 3 darts = 2 points, etc.)
- **Guest Mode**: Practice without saving scores to leaderboard
- **Persistent Leaderboard**: Track your best performances with Supabase integration
- **Responsive Design**: Works on desktop and mobile devices

## How to Play

1. **Select Game Mode**: Choose between 1-player or 2-player mode
2. **Enter Player Name(s)**: Sign in with your name or play as Guest
3. **Practice Checkouts**: Work through outs 61-100, recording how many darts each finish takes
4. **Score Points**: 
   - 2 darts = 3 points (Excellent)
   - 3 darts = 2 points (Great) 
   - 4-6 darts = 1 point (Good)
   - 7+ darts = 0 points (Miss)
5. **Track Progress**: View your total score out of 120 possible points

## Getting Started

### Prerequisites
- Modern web browser with JavaScript enabled
- No installation required - runs entirely in the browser

### Running Locally

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd catch40appindex
   ```

2. **Start a local web server:**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Open in browser:**
   Navigate to `http://localhost:8000` in your web browser

### Deployment

This is a static web application that can be deployed to any web hosting service:

- **GitHub Pages**: Push to a GitHub repository and enable Pages
- **Netlify**: Drag and drop the files to Netlify
- **Vercel**: Connect your Git repository
- **Firebase Hosting**: Use `firebase deploy`

## Game Rules

### Scoring System
The app uses a points-based system to encourage quick, accurate finishes:

- **3 Points**: Finished in exactly 2 darts (or 99 out in 3 darts)
- **2 Points**: Finished in exactly 3 darts  
- **1 Point**: Finished in 4, 5, or 6 darts
- **0 Points**: Took 7 or more darts (recorded as "Miss")

### Recommended Takeouts
Each out displays the optimal finishing combination:
- **61**: SB-D18 (Single Bull, Double 18)
- **71**: T13-D16 (Treble 13, Double 16) 
- **100**: T20-D20 (Treble 20, Double 20)
- And many more strategic combinations

## Technology Stack

- **Frontend**: Pure HTML, CSS, JavaScript (ES6+)
- **Styling**: Tailwind CSS via CDN
- **Data Storage**: LocalStorage for game state
- **Leaderboard**: Supabase REST API
- **Fonts**: Google Fonts (Inter)

## File Structure

```
catch40appindex/
├── index.html              # Main application file
├── catch40applogo.png      # App logo image
├── CGC official logo-1.png # Organization logo
├── README.md              # This file
├── .gitignore            # Git ignore rules
└── index.txt             # Additional notes/documentation
```

## Keyboard Shortcuts

- **0**: Record a miss (7+ darts)
- **2**: Record 2-dart finish  
- **3**: Record 3-dart finish
- **4**: Record 4-dart finish
- **5**: Record 5-dart finish
- **6**: Record 6-dart finish
- **Backspace**: Undo last entry

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you encounter any issues or have questions:
- Check the browser console for error messages
- Ensure JavaScript is enabled
- Try refreshing the page or clearing browser cache
- Submit an issue on GitHub

## Acknowledgments

- Built for dart players by dart players
- Inspired by traditional dart training methods
- Designed for CGC (Competitive Gaming Community)

---

**Happy Practicing! 🎯**