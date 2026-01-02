# ViP Officer Credit Tracking System - Proposal Presentation

A reveal.js presentation showcasing a modern, automated solution for tracking officer credit in the ViP guild (Guild Wars 2).

## 🎯 Purpose

This presentation is designed for Community Owners to understand the proposed system for replacing the current Google Forms-based credit tracking with an integrated Discord bot and web application solution.

## 🚀 View the Presentation

**Live Demo:** `https://[your-username].github.io/vip-tracker-proposal/`

(Replace `[your-username]` with your GitHub username once deployed)

## 📋 What's Included

The presentation covers:

1. **Current Pain Points** - Problems with the Google Forms system
2. **Solution Overview** - Discord bot + web dashboard approach
3. **PvE Event Automation** - Automated tracking with LT signups
4. **Probationary Officer Training** - Takeover feature for training
5. **WvW System** - Flexible submission for WvW events
6. **Other Submissions** - Admin, dev, recruiting, and participation tracking
7. **Real-Time Status** - Officers can check progress anytime
8. **Admin Dashboard** - Web interface for reviews and reports
9. **System Architecture** - High-level technical overview
10. **Timeline** - 10-14 weeks with phased rollout

## 🛠️ Technology

- **Framework:** [Reveal.js](https://revealjs.com/) v5.0.4
- **Styling:** Custom CSS with Discord-style mockups
- **Hosting:** GitHub Pages

## 📦 Repository Structure

```
vip-tracker-proposal/
├── index.html                 # Main presentation
├── assets/
│   ├── css/
│   │   ├── custom.css         # ViP-specific styling
│   │   └── discord-mockups.css # Discord interface mockups
│   └── js/
│       └── reveal-config.js    # Presentation configuration
├── docs/
│   └── setup.md               # GitHub Pages setup guide
└── README.md                  # This file
```

## 🚀 Deployment

See [docs/setup.md](docs/setup.md) for detailed GitHub Pages deployment instructions.

Quick start:

```bash
# Commit all files
git add .
git commit -m "Add presentation files"
git push origin main

# Then enable GitHub Pages in repository Settings → Pages
```

## 🎮 Navigation

- **Arrow Keys** or **Space**: Navigate slides
- **ESC**: Overview mode
- **?**: Show keyboard shortcuts
- **On-screen controls**: Bottom-right corner

## 🔧 Local Development

Test locally before deploying:

```bash
# Start a local server
python3 -m http.server 8000

# Open browser to http://localhost:8000
```

## 📝 Making Updates

To update the presentation:

1. Edit `index.html` or CSS files
2. Test locally (optional)
3. Commit and push changes
4. GitHub Pages will auto-deploy (1-2 minutes)

## 📄 Related Documentation

For the full system planning documentation, see the `tracker_planning` directory:
- System Requirements
- Database Schema
- Implementation Plan
- System Architecture

## 🤝 Contributing

This presentation is for internal ViP guild use. If you have suggestions or find issues, please discuss with the development team.

## 📧 Contact

Questions about the proposed system? Contact the ViP development team.
