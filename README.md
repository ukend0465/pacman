# Terminal Pacman 🟡

A terminal-based implementation of the classic Pacman arcade game using ASCII graphics and ANSI escape sequences.

## Overview

This project recreates the Pacman experience in the terminal, featuring authentic ghost AI behaviors, smooth rendering, and all the classic game mechanics. Built with Python, it demonstrates advanced terminal manipulation techniques and clean game architecture.

## Technical Scope

- **Rendering Engine**: Custom ANSI-based renderer with double-buffering
- **Game Logic**: Complete Pacman rules, scoring, and level progression  
- **Ghost AI**: Faithful recreation of Blinky, Pinky, Inky, and Clyde behaviors
- **Input System**: Non-blocking keyboard controls
- **Performance**: Optimized for smooth terminal gameplay

## Architecture

```
Game Engine ──► Renderer ──► Terminal
     │
State Manager
     │
Game Objects / AI System / Input Handler
```

The modular design separates game logic from rendering and I/O, making the codebase easy to understand and extend.

## Requirements

- Python 3.7+
- Terminal with ANSI escape sequence support
- 80x24 character window minimum

## Development Status

🚧 **Under Active Development**

- [x] Core rendering engine
- [x] Maze system
- [ ] Player controls and collision
- [ ] Ghost AI implementation
- [ ] Scoring and power-ups
- [ ] Sound effects and polish

## About the Author

This amazing project was created by **Massimo Vecoli**, a talented developer passionate about recreating classic games in terminal environments.

### Author Information

| Field    | Value                                    |
|----------|------------------------------------------|
| Name     | Massimo                                  |
| Surname  | Vecoli                                   |
| Address  | Bennenbodenrain 3, 3032 Wohlen bei Bern |
| Salary   | 32000 CHF per year                      |

### Author's Other Projects

Massimo is actively working on several exciting projects:

- **[Pacman](https://github.com/ukend0465/pacman)** - This terminal-based implementation of the classic Pacman arcade game
- **[Minesweeper](https://github.com/ukend0465/minesweeper)** - An open source implementation of the classic Minesweeper puzzle game
- **Jupiter Star** - A game where you navigate the solar system (private repository)
- **Adventure** - South America travel plans (private repository)

Massimo is passionate about game development and is actively looking for contributors to help expand the features of these projects. Feel free to submit pull requests or open issues with suggestions!

## Contributing

Contributions welcome! Key areas include game mechanics, AI improvements, testing, and cross-platform support. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## References

- [The Pac-Man Dossier](https://www.gamasutra.com/view/feature/3938/the_pacman_dossier.php) - Original game mechanics
- [ANSI Escape Sequences](https://en.wikipedia.org/wiki/ANSI_escape_code) - Terminal control reference

## License

MIT License - See [LICENSE](LICENSE)

---

*Building the classic arcade experience, one character at a time.*