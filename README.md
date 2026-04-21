# Furniture Progress Tracker System

A complete web-based furniture order tracking system for managing custom furniture projects.

## Features

### For Owners/Admins
- Add/delete furniture orders
- Assign craftsmen to projects
- Update progress with descriptions
- Generate unique tracking links for customers
- Manage user accounts (add owners/craftsmen)

### For Craftsmen
- View assigned furniture only
- Update progress on assigned projects

### For Customers
- Track orders using unique codes
- View real-time progress and updates
- No login required

## Demo Credentials

**Owner Access:**
- Username: `owner`
- Password: `12345`

**Craftsman Access:**
- Username: `craftsman1`, Password: `pass123`
- Username: `craftsman2`, Password: `ali123`

**Customer Tracking Code:**
- `EN84FMZ2` (tracks order F001)

## How to Use

1. **Owners & Craftsmen**: Use `index.html` to login and manage orders
2. **Customers**: Use `track.html` or click "Customer View" from links section

## Technology Stack

- HTML5
- CSS3
- JavaScript (ES6)
- LocalStorage for data persistence

## Installation

1. Clone this repository
2. Open `index.html` in a web browser
3. Or deploy to GitHub Pages for online access

## Deployment to GitHub Pages

1. Push these files to a GitHub repository
2. Go to Settings > Pages
3. Select branch as main
4. Site will be available at `https://[username].github.io/[repo-name]`

## Data Storage

All data is stored locally in your browser's localStorage. For production use, consider implementing a backend database.

## License

MIT
