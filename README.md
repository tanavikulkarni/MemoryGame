# 🧠 Flask Memory Game

A simple and fun **Memory Matching Game** built with **Flask** (Python) for the backend and **HTML/CSS/JavaScript** for the frontend. Flip cards, find matching pairs, and test your memory!

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Flask](https://img.shields.io/badge/Flask-2.x-black)
![License](https://img.shields.io/badge/License-MIT-green)

## 📋 Table of Contents

- [Features](#-features)
- [Demo](#-demo)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the App](#running-the-app)
- [How to Play](#-how-to-play)
- [Configuration](#-configuration)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)

## ✨ Features

- 🎴 Classic card-flip memory matching gameplay
- ⏱️ Move counter and timer to track performance
- 🏆 Win detection with a congratulations screen
- 🔄 Restart/reset game at any time
- 📱 Responsive design that works on desktop and mobile
- 🎨 Clean, simple UI built with vanilla CSS/JS

## 🎮 Demo

> Add a screenshot or GIF of the game here, for example:
>
> ![Gameplay Screenshot](static/img/screenshot.png)

## 🛠️ Tech Stack

- **Backend:** Python, Flask
- **Frontend:** HTML5, CSS3, JavaScript
- **Templating:** Jinja2

## 📁 Project Structure

```
flask-memory-game/
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
├── static/
│   ├── css/
│   │   └── style.css      # Game styling
│   ├── js/
│   │   └── game.js        # Game logic (card flip, match check, etc.)
│   └── img/
│       └── cards/         # Card images/icons
├── templates/
│   ├── base.html           # Base layout template
│   └── index.html          # Game board page
└── README.md
```

> Note: adjust this structure to match your actual project layout.

## 🚀 Getting Started

### Prerequisites

- Python 3.9 or higher
- pip (Python package manager)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/flask-memory-game.git
   cd flask-memory-game
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate      # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

### Running the App

```bash
flask run
```

Or, if you run the app directly:

```bash
python app.py
```

By default, the app will be available at:

```
http://127.0.0.1:5000/
```

## 🕹️ How to Play

1. Open the game in your browser.
2. Click on a card to flip it and reveal the image/symbol underneath.
3. Click a second card to try to find its match.
4. If the two cards match, they stay flipped. If not, they flip back over.
5. Keep flipping cards until all pairs are matched.
6. Try to complete the board in the fewest moves and shortest time!

## ⚙️ Configuration

You can customize gameplay by editing values such as:

| Setting          | Location         | Description                          |
|-------------------|------------------|---------------------------------------|
| Number of cards   | `game.js`        | Change grid size (e.g., 4x4, 6x6)     |
| Card images       | `static/img/cards/` | Swap in your own card artwork      |
| Timer/Move limit  | `game.js`        | Add difficulty levels                 |

## 🗺️ Roadmap

- [ ] Add difficulty levels (Easy / Medium / Hard)
- [ ] Add leaderboard with best times
- [ ] Add sound effects
- [ ] Add multiplayer mode
- [ ] Deploy live demo (Heroku / Render / Vercel)

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add some feature"`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

Made with ❤️ and Flask.
