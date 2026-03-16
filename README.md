# Squirrel Eat Squirrel

![GitHub release (latest by date)](https://img.shields.io/github/v/release/ShivamKR12/squirrel-eat-squirrel)
![CI](https://github.com/ShivamKR12/squirrel-eat-squirrel/actions/workflows/build.yml/badge.svg)

A fun and addictive arcade-style game built with Python and Pygame, where you control a squirrel on a mission to grow by eating smaller squirrels while avoiding larger ones!

## 🎮 Game Description

In **Squirrel Eat Squirrel**, you play as a hungry squirrel in a vibrant green world filled with other squirrels of varying sizes. Your goal is to eat squirrels smaller than yourself to grow bigger and stronger. But beware—larger squirrels will eat you instead, costing you health points!

- **Objective**: Grow your squirrel to a massive size of 300 to achieve "OMEGA SQUIRREL" status and win the game.
- **Challenge**: Manage your health (starting with 3 points) and avoid getting eaten by bigger squirrels.
- **Survival**: Each collision with a larger squirrel reduces your health. When health reaches zero, it's game over!

The game features smooth controls, dynamic squirrel spawning, and a camera that follows your squirrel as it grows and moves through the world.

## ✨ Features

- **Dynamic Gameplay**: Squirrels of random sizes spawn continuously, creating unpredictable challenges.
- **Growth Mechanics**: Eat smaller squirrels to increase your size and strength.
- **Health System**: Track your health with a visual meter; lose health when eaten by larger squirrels.
- **Invulnerability Mode**: Gain temporary invulnerability after taking damage to recover.
- **Winning Condition**: Reach size 300 to win and restart the game.
- **Smooth Controls**: Use WASD or arrow keys for movement.
- **Visual Effects**: Bouncing animations and directional facing for all squirrels.
- **Cross-Platform**: Runs on Windows, macOS, and Linux.

## 🕹️ How to Play

1. **Start the Game**: Launch the game executable or run the Python script.
2. **Controls**:
   - **Movement**: Use `WASD` or arrow keys to move your squirrel.
   - **Restart**: Press `R` to restart after winning or losing.
   - **Quit**: Press `ESC` or close the window to exit.
3. **Strategy**:
   - Target smaller squirrels (those with smaller sizes) to grow.
   - Avoid larger squirrels—they'll eat you and reduce your health.
   - Use invulnerability periods wisely after taking damage.
4. **Winning**: Grow to size 300 to win. The game will display a victory message and allow you to restart.
5. **Game Over**: If your health drops to 0, the game ends with a "Game Over" screen.

## 🚀 Installation and Running

### Option 1: Download the Executable (Recommended for Non-Developers)

1. Go to the [Releases](https://github.com/ShivamKR12/squirrel-eat-squirrel/releases) page.
2. Download the latest `squirrel-eats-squirrel.zip` file.
3. Extract the ZIP file.
4. Run `squirrel-eats-squirrel.exe` (Windows) or the equivalent executable for your platform.

No Python installation required!

### Option 2: Run from Source Code

#### Prerequisites
- Python 3.7 or higher
- Pygame Community Edition (pygame-ce)

#### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/ShivamKR12/squirrel-eat-squirrel.git
   cd squirrel-eat-squirrel
   ```

2. Install dependencies:
   ```bash
   pip install pygame-ce
   ```

3. Run the game:
   ```bash
   python squirrel-eats-squirrel.py
   ```

## 🛠️ Building from Source

To build your own executable using PyInstaller:

1. Install PyInstaller:
   ```bash
   pip install pyinstaller
   ```

2. Build the executable:
   ```bash
   pyinstaller squirrel-eats-squirrel.spec
   ```

3. The executable will be in the `dist/` folder.

The project includes a GitHub Actions workflow that automatically builds Windows executables on each push.

## 📸 Screenshots

*(Add screenshots here if available)*

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`.
3. Make your changes and test them.
4. Commit your changes: `git commit -m 'Add some feature'`.
5. Push to the branch: `git push origin feature/your-feature`.
6. Open a Pull Request.

### Development Setup
- Ensure you have Python and pygame-ce installed.
- Run the game to test changes.
- Check for any linting or style issues.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Credits

- **Developer**: ShivamKR12
- **Built with**: Python, Pygame Community Edition
- **Inspired by**: Classic arcade games like Snake and Agar.io

## 📞 Support

If you encounter any issues or have questions:
- Open an issue on [GitHub](https://github.com/ShivamKR12/squirrel-eat-squirrel/issues).
- Check the [Actions](https://github.com/ShivamKR12/squirrel-eat-squirrel/actions) for build status.

Enjoy playing Squirrel Eat Squirrel! 🐿️